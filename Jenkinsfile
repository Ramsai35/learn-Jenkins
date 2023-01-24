pipeline {

   agent {
   label 'ansible'

     }

   stages {

      stage('Hello') {
         steps {
            echo 'Hello world'
         }
     }
   }


   Post {
     always {
      echo "sending mail"
     }


   }

}