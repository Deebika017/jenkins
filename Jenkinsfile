pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './Build.sh'
            }
        }
        stage('Test') {
            steps {
                sh './Test.sh'
            }
        }
        stage('Deploy') {
            steps {
                sh './Deploy.sh'
            }
        }
    }
}
