pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo yum install httpd -y'
                sh 'sudo systemctl start httpd'
                sh 'sudo git clone https://github.com/ashwin1-dev/jenkin3.git  /var/www/html '
            }
        }
    }
}
