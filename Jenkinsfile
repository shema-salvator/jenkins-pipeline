pipeline {
 agent any // Runs on any available agent
 stages {
 stage('Build') {
    steps {
        echo "Building the project..."
        script {
            if (isUnix()) {
                sh 'ls -la'
            } else {
                bat 'dir'
            }
        }
    }
}

 stage('Test') {
 steps {
 echo "Running tests..."
 }
 }
 stage('Deploy') {
 steps {
 echo "Deploying..."
 }
 }
 }
}
