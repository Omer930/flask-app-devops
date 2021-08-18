pipeline {
    agent any

    stages {
        stage('Image Build') {
            agent { dockerfile true }
            steps {
                sh 'echo docker file build'
            }
        }
        stage('Host') {
            steps {
                sh 'echo host'
            }
        }
        stage('Sonarscanner') {
            steps {
                sh 'echo annas'
            }
        }
    }
}
