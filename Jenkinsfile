pipeline {
    agent any
    
    stages {
        stage('build') {
            steps {
                1..1000.each {it ->
                    echo "${it}: In building ${env.WORKSPACE}."
                }
            }
        }
        stage('test') {
            steps {
                echo "In testing."
            }
        }
    }
}
