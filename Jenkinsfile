pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                if (fileExists('sample.html')) {
                  echo 'Yes'
                    } else {
                    echo 'No'
                    }
            }
        }
    }
}
