pipeline { 
    stages {
        stage('apt_update debian servers') {
            node("Ansible"){
                sh 'ansible-playbook -i Ubuntu20 apt_updates.yml'
            }  
        }
    }
}