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
                ls
            }
        }
    }
}
