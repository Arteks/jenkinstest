pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello2') {
            steps {
                echo 'Hello World2'
            }
        }
        stage('Build ID') {
            steps {
                echo "The Build ID is: $(BUILD_ID)"
            }
        }
    }
}
