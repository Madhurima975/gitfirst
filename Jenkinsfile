pipeline {
    agent {
    docker {
        image 'maven:3.9.5'
    }
}

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

