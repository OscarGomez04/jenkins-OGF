pipeline {
    agent any

    stages {
        stage('Clonar el repositori') {
            steps {
                git branch: 'main', url: 'https://github.com/OscarGomez04/jenkins-OGF.git'
            }
        }

        stage('Compilar el codi') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
