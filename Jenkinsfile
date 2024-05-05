pipeline {
    agent {
        node {
            label 'jen-doc-agent'
        }
    }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage ('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage ('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}