pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                echo 'Test!'

                script {
                    sh(script: "python hello.py", returnStdout: true)
                }
                echo "python hello.py")
            }
        }
    }
}