pipeline {
    agent any 
    stages {
        stage ("Test") {
            steps {
                script {
                    echo "This branch is $(env.BRANCH_NAME)"
                }
            }
        }
    }
}
