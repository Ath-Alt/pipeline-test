pipeline { // Root of pipeline
    agent { docker { image'python:3.5.1' } } // Pipeline steps run inside this container
    stages {
        stage('build') { // Parts of pipeline
            steps { // Commands inside
                sh 'pip --version' // Shell commands <v
                sh 'python --version'
            }
        }
    }
}