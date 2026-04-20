pipeline {
    agent any

    triggers {
        githubPush()
    }

   stage('Clone') {
    steps {
        git branch: 'main', url: 'https://github.com/Maheshbabu777/learning-git.git'
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
