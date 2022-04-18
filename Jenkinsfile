pipeline {
    options {
        timeout(time: 1, unit: 'HOURS')
    }
    stages {
        stage('build and push') {
            when {
                branch 'master'
            }
            sh "docker build -t docker/getting-started ."
        }
    }
}
