pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'python:3'
                }
            }
            steps {
                sh 'pwd'
                /* sh 'python -m py_compile sources/add2vals.py sources/calc.py' */
            }
        }
    }
}
