pipeline {
    agent {
        label "slave1"
    }
    parameters {
        string (
            name: 'PERSON',
            defaultValue: 'swarna',
            description: 'what is my name'
        )
    }
    stages {
        stage ('param') {
            steps {
                echo "hellow ${params.PERSON}"
            }

        }
    }
}
