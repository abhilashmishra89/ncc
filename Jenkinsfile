pipeline {
    agent {
        node {
            label 'master'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'sshpass -p "ips@ameyo020" scp -r -o StrictHostKeyChecking=no sipstatus.py check*   root@192.168.188.130:/home/ncc/'
                
            }
        }
    }
}
