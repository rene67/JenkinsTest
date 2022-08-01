pipeline {
    { node { label 'TestAgent'} }

    stages {
        stage('Build') {
            steps {
                checkout scm
            }
        }
    }
}
