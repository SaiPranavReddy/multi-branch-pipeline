node {
  stage('Git-Checkout') {
   git branch: 'development', url: 'https://github.com/SaiPranavReddy/multi-branch-pipeline.git'
  }

  stage('Maven-Clean') {
   sh label: '', script: 'mvn clean'
  }
    
 stage('Maven-Compile') {
   sh label: '', script: 'mvn compile'
  }
  
   stage('Maven-Test') {
   sh label: '', script: 'mvn test'
  }
   stage('Maven-Package') {
   sh label: '', script: 'mvn package'
  }
           
}
