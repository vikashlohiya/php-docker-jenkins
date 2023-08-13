pipeline{
    
    agent any
    stages{
    
    stage("Code"){
        steps{
        echo "Cloning code"
        git url:"https://github.com/vikashlohiya/php-docker-jenkins.git",branch:"master"
        }
    }
    
    stage("build"){
      steps{
          sh "docker-compose down"
          sh "docker-compose up -d"
        }
    }
}
}