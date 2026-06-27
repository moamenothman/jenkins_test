pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run Script') {
            steps {
                sh '''
                chmod +x hello.sh
                ./hello.sh
                    '''
            }
        }
    }
}
