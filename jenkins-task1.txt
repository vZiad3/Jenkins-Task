pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'This is the building step'
            }
        }
        stage('run') {
            steps {
                echo 'this is the run stage step'
            }
        }
    }
}
