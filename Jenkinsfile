pipeline {
agent any

stages {
    stage('install npm') {
        steps {
        sh 'sudo npm install -g n '
            }
     }  
    stage('build') {
        steps {
        sh 'npm test '
            }
        }
}
}
