pipeline {
    agnet any
    stages {
        stage("build"){
            steps {
                echo "build"
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }

}
