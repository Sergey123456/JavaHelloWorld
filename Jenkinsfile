pipeline {
    agent any
    stages {
        stage ("checkout") {
            steps {
                bat script: """
                    echo "Hello world checkout!"
                """
            }
        }
        stage ("build") {
            steps {
                bat script: """
                    echo "Hello world build!"
                """
            }
        }
    }
}