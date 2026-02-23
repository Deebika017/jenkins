pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Running Build stage"
                sh 'python3 Build.py'
            }
        }

        stage('Test') {
            steps {
                echo "Running Test stage"
                sh 'python3 Test.py'
            }
        }

        stage('Deploy') {
            steps {
                echo "Running Deploy stage"
                sh 'python3 Deploy.py'
            }
        }
    }
}
