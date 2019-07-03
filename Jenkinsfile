pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    pwd
                    echo "no sé si funcione :S"
                    echo "a ver si ahora no se tarda tanto"
                    ls -lah
                '''
            }
        }
    }
}
