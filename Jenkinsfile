pipeline {
    agent any
    
    stages {
        stage('build') {
            steps {
                1..100.each {
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
