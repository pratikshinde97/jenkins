pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'java -version'
            }
        }
        
        stage('print') {
            steps {
                echo "heloo world"
            }
        }
      stage('list') {
            steps {
                echo "cd command"
                cd
                cd sportyfit_backend/
            }
        }
    }
}
