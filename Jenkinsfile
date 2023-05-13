pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                //sh 'cd webapp && npm install && npm run build'
                //sh 'sudo docker run -dt --name fd -p 80:80 -v /home/azureuser/jenkins/webapp/dist:/usr/share/nginx/html nginx'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
