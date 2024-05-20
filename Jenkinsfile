pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/rjtax78/pipeline.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
