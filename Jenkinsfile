pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Pulling code from Git...'
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // For demo, just create a file as "build"
                sh 'echo "Build successful!" > build_output.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // For demo, just check the file exists
                sh 'test -f build_output.txt && echo "Test Passed" || echo "Test Failed"'
            }
        }
    }
}
