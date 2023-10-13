pipeline {
    agent any 
    
    stages{
        stage("Clone Code"){
            steps {
                git url:"https://github.com/Sarojkarkicurtin/aws-elastic-beanstalk-express-js-sample.git", branch: "main"
            }
        }
        stage("Build"){
            steps {
                sh "docker build -t my-app ."
            }
        }
   }
}
