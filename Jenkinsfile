pipeline {
    agent { docker { image 'node:14-alpine' } }

    environment {
        GH_TOKEN = 'blahblah'
    }

    stages {
        stage('build') {
            steps {
              echo "hello world"
            }
        }
    }
}
