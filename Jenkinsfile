pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "this is build  step"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
    }
}
