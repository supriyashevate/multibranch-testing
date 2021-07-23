pipeline {

    agent {
        node {
            echo 'Hello dev'
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
