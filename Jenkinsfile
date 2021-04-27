pipeline { 
    agent { node { label 'Ansible' } }
    stages {
        stage('apt_update debian servers') {
            steps {
                sh 'ansible-playbook -i Ubuntu20 apt_updates.yml'
            }  
        }
    }
}