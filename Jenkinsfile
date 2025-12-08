pipeline{
  agent any
  triggers{
    pollSCM('* * * * *')
  }
  stages{
     stage('compile') {
      steps {
        echo "compiling the python pgm"
        sh 'python3 h1.py'
      }
    }
  }
  
}
