pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
  feature
               sh """
               echo "Building Artifact for project samplewebapp"
               """
               
           }
       }
       stage('Reading branch wise')

               sh "mvn clean package"
               echo "Building Artifact for project"
               
           }
       }
       stage('Reading branch wise infor')
       master
       {
       when
       {
       branch "feature*"
       }
       steps
       {
       echo " It is only for Feature branch"
       }
       }
 feature
       stage('Deploy Code') {
       
          steps {
               sh """
               echo "Deploying Code"
               """"

       stage('Deploy Code') {
	   when
	   {
	   branch "master"
	   	   }
          steps {
               sh "mvn tomcat7:deploy"
               echo "Deploying Code"
   master
               
          }
      }
      }
      }
