node {

  stage('SCM Checkout'){
       git 'https://github.com/omprakashmohapatra/JavaProject'
  }
  stage('Maven package'){
      mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHome}/bin/mvn clean package"
  }

}
