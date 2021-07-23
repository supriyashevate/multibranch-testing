pipeline {

    agent {
        node {
            label 'master'
        }
    }

    stages {
        
        stage('Deploying Branch') {
            steps {
                cleanWs()
                sh """
                echo "DEploying master branch"
                """
            }
        }

    }   
}
