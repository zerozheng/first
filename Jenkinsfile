pipeline {
    #agent { docker 'php' }
    agent any
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
