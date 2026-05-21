pipeline {

    agent any

    environment {
        JAVA_HOME = "/usr/bin/java"
    }

    stages {

        stage('git checkout') {

            steps {

                script {

                    println "Hello all welcome to pipelinescripting"

                    var1 = 20

                    println "myvar1 value is ${var1}"

                    /* parameter variable */

                    println "value of my selected environment is ${params.ENV}"

                    /* environment variables */

                    println "my java path is ${env.JAVA_HOME}"

                    /* default Jenkins variables */

                    println "my current workspace is ${WORKSPACE}"

                }
            }
        }
    }
}
