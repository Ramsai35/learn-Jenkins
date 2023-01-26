//pipeline {

  // agent {
 //  label 'ansible'

   //  }

   //stages {

     // stage('Hello') {
       //  steps {
       //     echo 'Hello world'
     //    }
   //  }
  // }


  // post {
   //  always {
   //   echo "sending mail"
  //   }


  // }

//}

pipeline {
    agent any
    stages {
       stage ('test') {
          steps {
            script {
               def abc = "Hello"
               def xyz= 123

               print "abc = ${abc}"
               print "xyz = ${xyz}"

               print abc

               }

            }
        }

    }
 }