pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                build 'pipeline'
            }
        }
        stage('Results') {
            steps {
                echo 'Testing..'
                build 'pipeline'
            }
        }
    }
}
