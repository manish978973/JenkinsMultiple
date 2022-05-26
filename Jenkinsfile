
pipeline {
    agent any 
    stages {
        stage('Build') { 
            when { changeset "*/ProA/**"}
            steps {
               echo "Hello"
            }
        }
        stage('Test') { 
            when { changeset "*/ProB/**"}
            steps {
                echo "Hello"
            }
        }
        stage('Deploy') { 
            when { changeset "*/ProC/**"}
            steps {
                 echo "Hello"
            }
        }
    }
}
