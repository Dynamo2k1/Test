pipeline {
    agent any

    parameters {
        string(name: 'GREETING', defaultValue: 'Hello, Jenkins!', description: 'Greeting message')
    }

    stages {
        stage('Example') {
            steps {
                echo "This is a test pipeline."
                echo "Parameter GREETING is: ${params.GREETING}"
            }
        }
    }
}
