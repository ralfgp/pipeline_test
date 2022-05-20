pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Do something 2"
      }
    }
    stage('Test'){
      steps{
        sh '''
        ls
        echo "Hola"
        pwd
        ls -lrt
        uname
        hostname
        touch 1
        '''
      }
    }
    stage('Deploy'){
      steps{
        echo "Do something 3"
      }
    }
  }
}
