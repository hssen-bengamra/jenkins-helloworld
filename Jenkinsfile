node {
   stage('Clean') {
      cleanWs()
  }
  stage('Clone'){
      git 'https://github.com/hssen-bengamra/jenkins-helloworld.git'
  }
  
  stage('Build'){
      sh '''javac Main.java'''
  }
  
  stage('Run'){
      sh '''java Main'''
  }
}
