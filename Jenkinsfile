pipeline1 {
agent any 
  stages{
    stage('git-clone'){
      steps {
    checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-id', url: 'https://github.com/tookiewill33/etech_web_app']]])
    }
    }
      }
    }
   
