pipeline {
    agent {
        lable 'new_server'
    }

    stages {
        stage('Build') {
            steps {
                script {
                    sh 'docker compose up --build -d'
                }
            }
        }
    }
}
