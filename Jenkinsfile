pipeline {
    agent any 
    
    environment {
        PROJECT_NAME = "Neptun"
        OWNER_NAME = "Kirill B"
    }
    
    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building....."
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing........"
                echo "Hello ${OWNER_NAME}"
                echo "Project name is ${PROJECT_NAME}"
                echo "End of Stage Build"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                sh 'echo "Deploying......"'
                // sh "python --version"
                echo "End of Stage Build"
            }
        }
    }
}
