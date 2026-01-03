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
            steps {
                //${env.variable}
                //${params.variable}
                echo "building the aplicationa"
                echo "welcome ${name} enrolled ${course}"
            }
        }
    }
}
