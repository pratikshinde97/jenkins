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
                echo "sh command"
                sudo sh pwd
                echo "cd"
                sudo sh cd
            }
        }
    }
}
