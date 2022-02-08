pipeline {
    agent none

    stages {
        stage('Test') {
            agent   {
                label 'nodejs'
    
            }
            
            steps {
                sh([
                    label: "install dependencies",
                    script: "npm install"
                ])
                sh([
                    label: "run tests",
                    script: "npm test"
                ])
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