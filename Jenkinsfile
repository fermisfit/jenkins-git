pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    pwd
                    echo "esta linea se supone que la cambié"
                    echo "a ver si ahora no se tarda tanto"
                    echo "Ya que funcione esta chingadera"
                    ls -lah
                '''
            }
        }
    }
}
