pipeline {
  agent any
  stages {
    stage('inicio-pipeline') {
      steps {
        echo 'es el primero'
      }
    }
    stage('segundo paso') {
      steps {
        echo 'estupendo esto'
      }
    }
    stage('tercer paso') {
      steps {
        sh '''###muestro la fecha
fecha1=`date`

echo $fecha1

'''
      }
    }
  }
}