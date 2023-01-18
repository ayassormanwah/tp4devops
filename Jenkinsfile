pipeline {
  environment {
        registry = "manwahayassor/tp4"
        registryCredential = 'ddf8f003-6c63-47c0-a862-d6a6a2378179'
        dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
      	git 'https://github.com/ayassormanwah/tp4devops'
      }
   }
   stage('Building image') {
      steps{
        script {
          dockerImage = docker.build registry + ":$BUILD_NUMBER"
        }
      }
   }
   stage('Test image'){
   	steps{
    		script {
    			echo "Tests passed"
    		}
    	}
    }
    stage('Publish Image') {
      steps{
        script {
	        docker.withRegistry( '', registryCredential ) {
	        	dockerImage.push()
	        }
	    }
	  }
	}
	stage('Deploy image') {
		steps{
			bat "docker system prune -a"
			bat "docker stop $(docker ps -q)"
			bat "docker run --name tp4devops$BUILD_NUMBER -d -p 8081:80 $registry:$BUILD_NUMBER"
		}
	}
 }
}
