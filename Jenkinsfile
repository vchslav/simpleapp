pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    env.WAR_NAME = sh(script: "python3.8 hello.py", returnStdout: true).toString().trim()
                    echo "${WAR_NAME}"
                }
            }
        }
    }
}