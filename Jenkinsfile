pipeline {
    agent any 
    stages {
        stage('Build') { 
            agent {
            label 'label1'
            }
            steps {
                echo "BUILD AGAIN"
            }
        }
        stage('Test') {
            agent {
            label 'label2'
            }
            steps {
                // 
               echo "TEST"
            }
        }
        stage('Deploy') { 
            steps {
                // 
               echo "Deploy"
            }
        }
    }
}
