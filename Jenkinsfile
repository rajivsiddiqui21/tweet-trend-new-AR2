pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone code') {
            steps {
                //echo 'Hello World'
                git branch: 'main', url: 'https://github.com/rajivsiddiqui21/tweet-trend-new-AR2.git'
            }
        }
    }
}
