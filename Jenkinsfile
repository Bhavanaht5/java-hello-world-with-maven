pipeline {
    agent any
environment{
    PATH = "/usr/bin:$PATH"
}
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Bhavanaht5/java-hello-world-with-maven.git'
            }
        }
        stage('build') {
            steps {
                sh "mvn clean install"
            }
        }
     }
}
