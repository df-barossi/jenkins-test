pipeline {
    agent any

    stages {
        stage('test') {
            steps { 
                echo ("hello world!")
                echo ("This is the job name: '${env.JOB_NAME}'")
                echo ("This is the job url: '${env.JOB_URL}'")
                echo ("This is the current build id: '${env.BUILD_ID}'")
                
            }  
        }
    }
}               