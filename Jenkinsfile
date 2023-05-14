pipeline {
    agent any
    triggers {
        pollSCM '*/3 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                echo "doing build stuff"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
