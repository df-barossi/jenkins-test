pipeline {
    agent any

    stages {
        stage('test') {
            steps { 
                echo 'hello world!'
                echo 'This is the job name: %s' % env.JOB_NAME
                echo 'This is the job url: %s' % env.JOB_URL
            }  
        }
    }
}               