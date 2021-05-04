pipeline {
    agent any

    stages {
        stage('CICD') {
            steps {
                sh 'docker-compose up'
                
            }
            // post{
            //    success{
            //        slackSend(color:"66ffff",message:"Hello from jenkins")
            //    }

            // }
        }
    }
}


