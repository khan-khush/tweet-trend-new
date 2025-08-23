pipeline {
    agent {
        node {
            label 'maven'
        }
        }
    }

    stages {
        stage('clone-code') {
            steps {
                     git branch: 'main', url: 'https://github.com/khan-khush/tweet-trend-new.git'
                }
        }
    }

