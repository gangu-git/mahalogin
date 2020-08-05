pipeline {
    agent { label 'ansible' }
    stages{
      stage	('get some code on git hub'){
         steps {    
        git 'https://github.com/gangu-git/mahalogin.git'
      }
    }
      stage ('excuting mvn comands'){
        steps { 
            sh 'mvn package'
       }
   }
  }
}  
