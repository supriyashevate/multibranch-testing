pipeline {

    agent {
        node {
            label 'dev'
        }
    }

    stages {
        
        stage('Deploying Branch') {
            steps {
                cleanWs()
                sh """
                echo "Deploying dev branch"
                """
            }
        }

    }   
}
