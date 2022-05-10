pipeline {
agent any

stages {
    stage('install npm') {
        steps {
            sh 'npm config ls'
        sh 'npm install -g n '
            }
     }  
    stage('build') {
        steps {
        sh 'npm test '
            }
        }
}
}
