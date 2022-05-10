pipeline {
agent any

stages {
    stage('install npm') {
        steps {
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
