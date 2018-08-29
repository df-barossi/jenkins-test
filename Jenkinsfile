pipeline {
    agent any

    stages {
        stage('test') {
            steps { 
                echo 'hello world!'
                echo 'This is the job url: %s' % $(JOB_URL)
            }  
        }
    }
}