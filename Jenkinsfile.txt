properties([pipelineTriggers([pollSCM('*/30 * * * * ')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python3 file.py'
            }
        }
    }
}
