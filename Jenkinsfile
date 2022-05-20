pipeline {
    agent any
    
    stages {
        stage ("Checkout") {
            steps {
                git url: 'https://github.com/minkahbaraka/python-calculator.git'
            }
        }
        

        stage ("Build") {
            steps {
              sh 'python mutliply.py'
            }
        }
    }
}    