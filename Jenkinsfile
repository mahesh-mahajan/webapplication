node {
  stage ('SCM Scheckout'){
    git 'https://github.com/mahesh-mahajan/webapplication.git' 
  }
  stage ('Build Application'){
    sh 'mvn clean install -Dmaven.test.skip=true -U'
  }

}
