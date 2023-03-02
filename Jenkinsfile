pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Build staging'
            }
        }
        stage('deploy to production') {
            steps {
                echo 'Deploy to staging'
            }
        }
    }
    post {
        always {
            // previous to version 2.0.0 you must provide parameters to this command (see below)!
//             jiraSendBuildInfo(site: 'chansopheaktrachheng.atlassian.net') 
            echo 'Post  '
        }
    }
}
