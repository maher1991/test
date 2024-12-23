pipeline {
    agent {
        docker {
            image 'maven'
        }
    }

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Build') {
            steps {
                sh "mvn --version"
            }

        }
    }
}
