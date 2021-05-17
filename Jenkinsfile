pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                def exists = fileExists 'sample.html'

                if (exists) {
                  echo 'Yes'
                            } else {
                   echo 'No'
                        }
                }
        }
    }
}
