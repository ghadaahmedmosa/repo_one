pipeline {
    agent any

    stages {
      
        stage('test') {
            steps {
                echo 'test'
                sh """
                    echo "build number is ${BUILD_NUMBER}"
                    docker ps
                    curl --help
                """
            }
      
        }
    }
}
