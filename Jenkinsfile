pipeline {
    agent   {
        label 'nodejs'
    
    }

    stages {
        stage('Test') {
            steps {
                echo 'Testing..'
                sh """
                    echo "What a wonderful day !"
                """
            }
        }
    //     stage('run') {
    //         steps {
    //             echo 'running..'
    //             sh """
    //                 docker run --rm hello-world
    //             """
    //         }
    //     }
    //     stage('') {
    //         steps {
    // // One or more steps need to be included within the steps block.
    //         }

    //     agent {
    //         label 'kaniko'
    //     }
    }
}