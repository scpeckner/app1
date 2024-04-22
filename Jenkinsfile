pipeline {
    agent any
    stages {
        stage("build"){
            steps {
                echo "2nd time build"
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }

}
