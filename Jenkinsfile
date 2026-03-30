pipeline {
    agent any

    stages {
        stage('Run Script') {
            steps {
                // Make sure script is executable
                sh 'chmod +x script.sh'
                // Run the script
                sh './script.sh'
            }
        }
    }
}
