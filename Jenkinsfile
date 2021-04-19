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
             stage('cd') {
            steps {
                dir("/home/ubuntu/sportyfit_backend") {
                 sh "pwd"
                 }
               
            }
        }
    }
}
