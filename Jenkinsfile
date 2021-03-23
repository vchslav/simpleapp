pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                while (true) {
                    script {
                        env.OUTPUT = sh(script: "python3.8 hello.py", returnStdout: true).toString().trim()
                        echo "${OUTPUT}"
                        sh "sleep 30"
                    }
                }
            }
        }
    }
}