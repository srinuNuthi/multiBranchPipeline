pipeline {
    agent any
    
    stages {
        stage('git') {
            steps {
                git url: 'https://github.com/srinuNuthi/multiBranchPipeline.git',
                    branch: 'main'
            }
        }
        stage('print hello world') {
            steps {
                echo " i am from main branch"
            }
        }
    }
}



