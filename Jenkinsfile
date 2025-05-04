pipeline {
    agent any

    environment {
        APP_NAME = 'JenkinsDemoApp'
        DEPLOY_ENV = 'staging'
    }

    stages {
        stage('Build') {
            steps {
                echo "Building $APP_NAME..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing $APP_NAME..."
                echo 'Running unit tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying $APP_NAME to $DEPLOY_ENV environment..."
            }
        }
    }
}
