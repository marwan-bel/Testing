pipeline {
  agent any
      tools {         // Install the Maven version configured as "M3" and add it to the path.    
           maven "myMaven"  
           git  "myGit"
           
             
            }
 
  stages {
    stage('Checkout Scm') {
      steps {
        git 'https://github.com/marwan-bel/Testing'
      }
    }

    stage('Shell script 0') {
      steps {
        sh 'mvn clean compile'
	      sh 'mvn -v'
        sh 'mvn -v'

      }
    }

  }
}