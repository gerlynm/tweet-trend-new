pipeline {
    agent {
        node {
            label "maven"
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/gerlynm/tweet-trend-new.git'
            }
        }
    }
}
