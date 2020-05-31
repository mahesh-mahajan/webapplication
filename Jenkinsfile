node {
  stage ('SCM Scheckout'){
    git 'https://mahesh-mahajan@github.com/mahesh-mahajan/webapplication' 
  }
  stage ('Build Application'){
    sh 'mvn clean install -Dmaven.test.skip=true -U'
  }

}
