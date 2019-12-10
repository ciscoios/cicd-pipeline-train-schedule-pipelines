pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Running gradle build"
                ./gradlew build --no-daemon
            }
        }
        stage('Test') { 
            steps {
                echo "Test step" 
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy step" 
            }
        }
    }
}
