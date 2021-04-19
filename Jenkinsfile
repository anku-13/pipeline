pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo "Compiled Success";
            }
        }
        stage('Unit') {
            steps {
                echo "UNit Success";
            }
        }
        stage('Quality') {
            steps {
                echo "Quality Success";
            }
        }
        stage('Deploy') {
            steps {
                echo "Quality Success";
            }
        }
    }
    post{
        always{
            echo 'This is alwaya run'
        }
        success {
            echo 'Tsuccess'
        }
        failure {
            echo 'sfcs'
        }
       
    }
        
      
       }   
