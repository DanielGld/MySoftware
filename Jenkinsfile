properties([pipelineTriggers([pollSCM('*/30 * * * * ')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python file.py'
            }
        }
    }
}
