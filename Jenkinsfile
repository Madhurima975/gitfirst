pipeline {
    agent any

    stages {

        stage('Clone from GitHub') {
            steps {
                echo 'Cloning GitHub repository...'
                git branch: 'main',
                    url: 'https://github.com/Madhurima975/gitfirst.git'
            }
        }

        stage('Run basic command') {
            steps {
                sh '''
                  pwd
                  ls -l
                '''
            }
        }
    }
}

