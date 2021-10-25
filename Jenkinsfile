pipeline {
	agent any
		stages {
			stage('Build'){
  
				steps{
				    echo 'build'

				}
			}
			stage("Junit Result"){
			    steps{
			        echo 'gathering test results'
			    }
			}



			stage('Server shutdown'){
				steps{
				echo 'shutting down tomcat'

			}
		}
			stage('Deploy'){
				steps{
				echo 'Deploy'

				}
			}
		
		}
}
