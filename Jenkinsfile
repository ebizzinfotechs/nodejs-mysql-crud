pipeline {
	agent {
		node {
			stage('Test') {
				steps {
				sh 'npm install'
				sh 'npm test'
				}
			}
		}
	}

}
