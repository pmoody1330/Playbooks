pipeline { 
    agent any
    stages {
        stage('apt_update debian servers') {
            
                sh 'ansible-playbook -i Ubuntu20 apt_updates.yml'
              
        }
    }
}