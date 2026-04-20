pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/Maheshbabu777/learning-git'
            }
        }

        stage('Install') {
            steps {
                sh 'echo "Installing..."'
            }
        }

        stage('Done') {
            steps {
                echo "Pipeline ran successfully!"
            }
        }
    }
}
