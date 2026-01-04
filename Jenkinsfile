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
        choice (
            name: 'CHOICE',
            choices: ['oone', 'two', 'threee'],
            descruotuib : 'pic some number'
        )
        booleanParam(
            name: 'TOGLE',
            defaultValue: true,
            description: 'toogkle this '

        )
        text(
            name: 'RELEASE',
            defaultValue: '',
            descruotuib : 'enter some details'

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
