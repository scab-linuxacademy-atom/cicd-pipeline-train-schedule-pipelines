pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'Running build Auto-Mation'
                sh './gradlew build --daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
