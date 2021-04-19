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
                echo "cd command"
                sh cd
                sh './sportyfit_backend/'
               
            }
        }
    }
}
