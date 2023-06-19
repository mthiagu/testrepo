pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        bat "C:\\thiagu\\sw\\perl-5.32\\perl\\bin\\perl --version"
        }
       }
       stage('hello') {
        steps {
         bat "C:\\thiagu\\sw\\perl-5.32\\perl\\bin\\perl test.pl"
         }
       }
   }
}
        
