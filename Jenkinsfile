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
      stage('pwd') {
            steps {
                echo "sh command"
                sh pwd
               
            }
        }
             stage('cd') {
            steps {
                echo "cd command"
                sh cd
               
            }
        }
    }
}
