pipeline {
    agent any

    stages {

        stage('Deploy Application') {
            steps {
                sh 'ansible-playbook -i inventory deploy.yml'
            }
        }
    }
}
