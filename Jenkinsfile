pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        bat "perl --version"
        }
       }
       stage('hello') {
        steps {
         bat "perl test.pl"
         AuditTools() 
         }
       }
   }
}
        
void AuditTools(){
  bat "git --version"
  bat "perl --version"
  bat "hostname"
  bat "date /t"
}
