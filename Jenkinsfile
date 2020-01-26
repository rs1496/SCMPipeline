node
 { 
  stage('Checkout'){
     {
         checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'eb94a833-d297-4872-90c9-39cb8a7260c4', url: 'https://github.com/rs1496/SCMPipeline.git']]])
        
     }
  }
     stage('Code Analysis'){
         echo "static code analysis"
     }
     stage('Test'){
         echo ("Testing the code")
     }
     stage('Deploy'){
         echo "Deploying the code"
     }
 }
