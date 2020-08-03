pipeline {
    agent any
    stages {
        stage('build master') {
            when {
                branch 'master'
            }
            steps {
                echo "ruuuning the build master"
            }
        }
        stage('dev branch') {
            when {
                brnach 'dev'
            }
            steps {
                echo "runnnin in dev branch"
            }
        }
    }
}
