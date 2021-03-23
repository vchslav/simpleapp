pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                echo 'Test!'

                script {
                    sh(script: "python3.8 hello.py", returnStdout: true)
                }
            }
        }
    }
}