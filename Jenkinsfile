pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('bye') {
            steps {
                echo 'good World'
            }
        }
        stage('seeya') {
            steps {
                echo 'seeya World'
            }
        }
    }
    post {
		always {
			echo "i will always run"
		}
	}
}
