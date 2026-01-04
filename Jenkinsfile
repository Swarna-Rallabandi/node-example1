pipeline {
    agent {
        label "slave1"
    }
    parameters {
        string (
            name: 'person',
            defaultValue: 'swarna'
            description: 'what is my name'
        )
    }
    stages {
        stage ('param') {
            steps {
                echo "hellow ${params.name} swarna"
            }

        }
    }
}
