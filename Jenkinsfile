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
