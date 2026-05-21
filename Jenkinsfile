pipeline {

    agent any

    stages {

        stage('working with loops') {

            steps {

                script {

                    for(i=1; i<=5; i++) {

                        println "my i value is ${i}"
                    }

                    list1 = ["devops", "aws", "scripting"]

                    for(ele in list1) {

                        println "my list element is ${ele}"
                    }
                }
            }
        }
    }
}
