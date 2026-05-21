pipeline {

    agent any

    parameters {
        choice(
            choices: ['dev', 'sit', 'prod', 'pt'],
            description: 'My environment',
            name: 'ENV'
        )
    }

    stages {

        stage('git checkout') {

            steps {

                script {

                    println "Hello all welcome to pipelinescripting"

                    var1 = 20

                    println "myvar1 value is ${var1}"

                    /* accessing parameter variable */

                    println "value of my selected environment is ${params.ENV}"

                }
            }
        }
    }
}
