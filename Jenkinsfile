pipeline {
    agent {
        node {
            label "maven"
        }
    }
environment {
    PATH = "/opt/apache-maven-3.9.7/bin:$PATH"
    //PATH = "/home/ubuntu/maven-1/bin:$PATH"
}    

    stages {
        stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
