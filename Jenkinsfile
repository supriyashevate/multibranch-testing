pipeline {

    agent {
        node {
            echo 'Hello'
        }
    }

    stages {
        
        stage('Deploying Branch') {
            steps {
                cleanWs()
                sh """
                echo "Deploying feature branch"
                """
            }
        }

    }   
}
