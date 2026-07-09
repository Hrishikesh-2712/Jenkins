pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "this is building code"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "This is testing phase"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "this is Deployment phase"'
            }
        }
    }
}
