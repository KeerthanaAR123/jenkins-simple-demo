pipeline{
  agent any
  stages{
    stage('clone') {
      steps {
        git url: 'https://github.com/KeerthanaAR123/jenkins-simple-demo.git', 
        branch: 'main'
      }
    }
    stages('Run script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
