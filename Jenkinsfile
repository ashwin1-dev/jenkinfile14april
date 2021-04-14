pipeline {
    agent any
    
    tools {
          maven "jenkin-maven"
    }
    
    
    stages {
        stage('SCM') {
            steps {
                https://github.com/ashwin1-dev/31-march-maven2.git
                 }
         }
        
        stage('Build') {
            steps {
                sh "build clean package"
            }
        }
        
        stage('Deploy') {
            steps {
                 sh "sudo cp                /usr/share/tomcat/webapps/"
                 }
        }
    }
}
