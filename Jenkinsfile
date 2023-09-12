pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                    echo 'sample printing !!!!'
                }
        }
        stage('Clone') {
            steps {
                    git credentialsId: 'ec2-user', url: 'git@bitbucket.org:vprasadk111/testgit.git'
                }
        }
    }
}
