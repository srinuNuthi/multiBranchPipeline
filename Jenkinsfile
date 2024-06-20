pipeline {
    agent any
    
    stages {
        stage('git') {
            steps {
                git url: 'https://github.com/srinuNuthi/multiBranchPipeline.git',
                    branch: 'test'
            }
        }
        stage('print hello world') {
            steps {
                echo " i am from test branch"
            }
        }
    }
}
