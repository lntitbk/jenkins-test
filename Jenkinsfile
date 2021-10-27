pipeline {
    agent any
    environment {
        NEW_VERSION = '1.3.0'
    }
    stages {
        stage("build") {
            steps {
                echo 'building the application ..'
                echo "building version ${NEW_VERSION}"
            }
        }
        stage("test") {
            steps {
                echo 'test the application ..'
                echo "test version ${NEW_VERSION}"
            }
        }
        stage("desploy") {
            steps {
                echo 'desploy the application ..'
                echo "desploy version ${NEW_VERSION}"
            }
        }
    }
}
