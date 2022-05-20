pipeline {
    agent any
    // triggers {
    //      pollSCM('* * * * *')
    // }
     // added comment here to test polling
     // added another comment to test polling since the above didn't work
     //after manual build this worked too good
    stages {
        stage ("Checkout") {
            steps {
                git url: 'https://github.com/minkahbaraka/python-calculator.git'
            }
        }
        

        stage ("Build") {
            steps {
               sh echo "This is a build step"
            }
        }
    }
}    