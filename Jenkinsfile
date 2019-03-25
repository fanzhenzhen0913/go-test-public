pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bash 'echo "Hello World"'
                bash '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
