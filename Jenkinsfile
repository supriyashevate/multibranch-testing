pipeline {

    agent {
        node {
            label 'feature'
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
