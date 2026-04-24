pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                sh 'pip3 install -r requirements.txt || true'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
