pipeline {
    agent any

    stages {
    
        stage('IntegrationTest') {
            steps {
                echo 'IntegrationTest'
            
            }
			}
            
            stage('DeployTestServer') {
            steps {
                echo 'DeployTestServer'
                
            }
			}
            
            stage('SeliniumTest') {
            steps {
                echo 'SeliniumTest.'
                bat "mvn test"
                
            }
			}
            
            stage('DeployProdServer') {
            steps {
                echo 'DeployProdServer'
                
            }
			}
        
	}
}
  
