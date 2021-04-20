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
                sh 'cd /home/ubuntu/sportyfit_backend'
                sh 'pm2 log'
            }
        }
        
        stage('cd') {
            steps {
                dir("/home/ubuntu/sportyfit_backend") {
                 sh "pwd"
                 }
            }
        }
    }
}
