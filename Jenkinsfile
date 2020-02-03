pipeline {
   agent{
       kubernetes {
          containerTemplate {
            name 'maven'
            image 'maven:3.3.9-jdk-8-alpine'
            ttyEnabled true
            command 'cat'
          }
        }
   }

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
