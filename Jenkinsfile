pipeline {
    agent any 
    stages {
        stage ("Test") {
            steps {
                script {
                    sh "echo 'This branch is $(BRANCH_NAME)'"
                }
            }
        }
    }
}
