pipeline {
    agent any

    options {
        skipDefaultCheckout(true)
    }

    stages {

        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'C:\\Users\\saaiJ\\AppData\\Local\\Programs\\Python\\Launcher\\py.exe app.py 10 20'
            }
        }

    }
}