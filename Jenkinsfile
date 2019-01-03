node {

  stage('SCM Checkout'){
       git 'https://github.com/omprakashmohapatra/JavaProject'
  }
  stage('Maven package'){
      mvnHome = tool name: 'maven3', type: 'maven'
      ${mvnHome}/bin/mvn clean package
  }

}
