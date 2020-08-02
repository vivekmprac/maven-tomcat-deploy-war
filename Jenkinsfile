pipeline {
    agent any
    stages {
        stage('build master') {
            when {
                branch 'master'
            }
            steps {
                echo "building master"
            }
            
        }
        stage('build dev') {
            when {
                branch 'dev'
            }
            steps {
                echo "building dev"
            }
            
        }
        
    }
}
