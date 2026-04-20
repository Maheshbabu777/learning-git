pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }

        stage('Done') {
            steps {
                echo "CI/CD Pipeline executed successfully!"
            }
        }
    }
}
