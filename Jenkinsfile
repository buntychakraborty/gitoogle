pipeline {
    agent {
        docker {
            image 'node:latest'
            args '-p 3000:3000'
        }
    }
 
    stages {
        stage('Build') {
            steps {
                sh "chown -R 127:135 '/.npm'"
                sh 'npm install'
            }
        }
        stage('Test') {
                    steps {
                        echo 'testing'
                    }
                }
                stage('Deliver') {
                            steps {
                                echo 'Delivery'
                            }
                        }

    }
}
