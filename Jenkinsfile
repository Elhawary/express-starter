pipeline {
    agent any

    

    stages {
      
        stage('NPM Install') {
            steps {
                echo 'npm ci'
            }
        }

        stage('Lint') {
            steps {
                echo 'npm run lint'
            }
        }

        stage('Unit Tests') {
            steps {
                echo 'npm run test'
            }
        }
    }
}
