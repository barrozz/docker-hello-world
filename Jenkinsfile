pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh """
                    docker build -t hello-world
                """
            }
        }
        stage('run') {
            steps {
                echo 'running..'
                sh """
                    docker run --rm hello-world
                """
            }
        }
    }
}
