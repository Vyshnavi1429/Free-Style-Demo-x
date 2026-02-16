# Free-Style-Demo-x
# code
 pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Vyshnavi1429/Free-Style-Demo-x.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
