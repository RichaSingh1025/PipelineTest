node{
  stage('SCM Checkout'){
    
    git 'https://github.com/RichaSingh1025/PipelineTest'
  }
  stage('Compile-Package'){
    def mvnhome = tool name: '', type: 'maven'
    sh '${mvnhome}/bin/mvn package'
  }
  
}
