node {

  stage('SCM Checkout'){
       git 'https://github.com/omprakashmohapatra/JavaProject'
  }
  stage('Maven package'){
      tool name: 'maven3', type: 'maven'
      mvn package
  }

}
