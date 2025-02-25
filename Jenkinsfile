pipeline{
  agent any
  stages{
    stage('clone')
    {
      steps
      {
        git 'https://github.com/mamatha-19/demo1_rep.git'
      }
    }
    stage('build')
    {
      steps{
        sh 'javac sri.java'
      }
    }
    stage('run')
    {
      steps{
        sh 'java sri'
      }
    }
  }
}
