pipeline{
  agent any
  triggers{
    pollSCM('H/2 * * * *')
  }
  stages{
     stage('compile') {
      steps {
        echo "compiling the python programmm"
        sh 'python3 h1.py'
      }
    }
  }
  
}
