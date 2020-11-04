pipeline {
    agent { docker { image 'node:14' } }

    environment {
        GH_TOKEN = 'blahblah'
    }

    stages {
        stage('build') {
            steps {
                echo "Running ${env.BUILD_ID}"
                echo "GitHub Token: ${GH_TOKEN}"
                sh 'npm install'
                sh 'npm test'
            }
        }
    }
}
