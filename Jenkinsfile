pipeline {
    agent {
        label 'slave1'
    }
    environment {
        course = "kubernetes"
        GITHUB_CREDS= credentials('swarna-ssh-creds')
    }
    stages {
        stage('Build'){
            steps {
                echo "my github credentials are ${GITHUB_CREDS}"
                echo "username ${GITHUB_CREDS_USR}"
                echo "password ${GITHUB_CREDS_PSW}"
            }

        }
    }
}
