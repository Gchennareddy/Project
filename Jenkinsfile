node{
   stage('SCM Checkout'){
     git 'https://github.com/Gchennareddy/Project'
   }
   stage('Compile-Package'){
     //get maven home path
     def mvnHome = tool name: 'Maven 3', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
   } 
  /* stage('Email Notification'){
     mail bcc: '', body: 'Jenkins file for email Notification alerts', cc: '', from: '', replyTo: '', subject: 'jenkinsfile', to: 'reddy461g@gmail.com'
   
   } */
}

