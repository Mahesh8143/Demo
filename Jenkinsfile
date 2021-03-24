pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
                echo "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                echo "mvn test"
            }
        }
        stage('Package') { 
            steps {
                echo "mvn package"
            }
        }
    }
}
