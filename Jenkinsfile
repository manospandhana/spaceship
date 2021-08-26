pipeline {
    agent any
    stages {
        stage ("maven test"){
            steps {
            sh "mvn test"
            }
        }
        stage ("maven package"){
        steps {
            sh "mvn package"
        }
        }
    }
}