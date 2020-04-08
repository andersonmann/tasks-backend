pipeline{
    agent any
    stages {
        stage ('Build Backend') {
            steps {
                sh label: '', script: 'mvn clean package -DskipTests=true'
            }
        }
    }
}