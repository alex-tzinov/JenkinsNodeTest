pipeline {
    agent { docker { image 'node:9.11.1' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
		sh 'yarn install'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "This is the deploy step"'
            }
        }
    }
}
