pipeline {
    agent any
    
    stages {
	
        stage('Checkout Code') {
            steps {
                git url: 'https://github.com/archna-chauhan/Jenkinstest.git', branch: 'main'
            }
        }

        stage('Install Python & Dependencies') {
            steps {
                bat 'python -V'
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python hello_word.py'
            }
        }
    }
}
