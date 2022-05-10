pipeline {
agent any

    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
				
				 sh 'apt-get update'

				sh 'apt-get install nodejs'

				sh 'apt-get install npm'
            }
        }
    }
}
