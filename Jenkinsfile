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
          stage('sudo') {
            steps {
                sh 'cd'
                sh 'pwd'
                sh 'cd /home/ubuntu/sportyfit_backend/'
                sh 'pwd'
            }
        }
       
    }
}
