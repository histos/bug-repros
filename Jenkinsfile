pipeline {
    agent any
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On Windows') {
                    when {
                      branch 'cake'
                    }
                    steps {
                        echo 'hello world'
                    }
                }
                stage('Test On Linux') {
                    steps {
                        echo 'hello world'
                    }
                }
            }
        }
    }
}
