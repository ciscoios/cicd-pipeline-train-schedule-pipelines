/* Declarative pipeline ### */
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Running gradle build"
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
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
