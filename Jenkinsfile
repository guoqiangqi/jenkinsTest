pipeline {
    agent { docker 'maven:3.6.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}