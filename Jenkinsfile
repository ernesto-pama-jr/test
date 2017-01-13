node { // <1>
    stage('Build') { // <2>
        /* .. snip .. */
    }
    stage('Test') {
        /* .. snip .. */
    }
    stage('Deploy') {
        ansiblePlaybook credentialsId: 'jenkins-ssh-key', inventory: '/var/ansible/test/hosts', playbook: '/var/ansible/test/deployment.yml'
    }
}