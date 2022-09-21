pipeline {

     agent {

      node {

         label 'master'
          customWorkspace '/mnt/akshay'
   }

 }

 
 
 
  stages {
       stage('install '){

           steps{
             
          sh "rm -rf /root/.m2"
             sh  "mvn  clean install"
      
    }
  }

   }
 }
