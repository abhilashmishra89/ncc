pipeline {
    agent {
        node {
            label 'master'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'scp -r -o StrictHostKeyChecking=no ../git-ncc/* root@192.168.188.130:/home/git-ncc/'
                
            }
        }
    }
}
