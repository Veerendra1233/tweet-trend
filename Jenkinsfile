pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/veerendra1233/tweet-trend.git [github.com]'
            }
        }
    }
}
