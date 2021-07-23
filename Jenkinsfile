pipeline {

    agent {
        node {
            echo 'Hello from feature'
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
