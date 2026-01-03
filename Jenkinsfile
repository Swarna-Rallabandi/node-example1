pipeline {
    agent {
         label 'slave1'
    }
    environment {
        course = "kubernetes"
        name= "swarna"
    }
    stages {
        stage('Build'){
            environemt{
                cloud = "GCP"
            }
            steps {
                //${env.variable}
                //${params.variable}
                echo "building the aplicationa"
                echo "welcome ${name} enrolled ${course}"
            }
        }
        stage ('SecondStage'){
            steps {
                echo " welcome to ${name}"
                echo " you are certified in ${cloud}"
            }
        }
    }
}
