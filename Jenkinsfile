pipeline {
    options {
        ansiColor('xterm')
        buildDiscarder(logRotator(daysToKeepStr: '8', numToKeepStr: '5', artifactDaysToKeepStr: '7', artifactNumToKeepStr: '8'))
    }
    agent {
        dockerfile {
            filename 'Dockerfile'
        }
    }
    stages {
        stage('Run') {
            steps {
                sh 'echo $coucou'
            }
        }
    }
}