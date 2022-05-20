pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh '''
        echo "Hola"
        echo $prueba
        pwd
        ls -lrt
        echo $password
        uname
        hostname
        touch 1
        '''
      }
    }
    stage('Test'){
      steps{
        echo "Do something 2"
      }
    }
    stage('Deploy'){
      steps{
        echo "Do something 3"
      }
    }
  }
}
