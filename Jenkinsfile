pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                def exists = fileExists 'file'

                if (exists) {
                         echo 'Yes'
                            } else {
                          echo 'No'
                            }
            }
        }
    }
}
