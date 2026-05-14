pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/shreeesankpal/practical6q1.git'
            }
        }

        stage('Deploy using Ansible') {
            steps {
                sh 'ansible-playbook -i inventory deploy.yml'
            }
        }
    }
}
