pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage ('Build'){
            steps{
                echp "building the applicaiton"
            }
        }
        stage('Scans'){
          steps {
            echo "performing the scans"
          }
        }
        stage ('DeploytoDev'){
            steps {
                echo "deploy to dev"
            }
        }
          stage ('DeploytoTest'){
            steps {
                echo "deploy to Test"
            }
        }
          stage ('DeploytoStage'){
            steps {
                echo "deploy to stage"
            }
        }
          stage ('Deploytoprod'){
            steps {
                echo "deploy to prod"
            }
        }
    }
}
