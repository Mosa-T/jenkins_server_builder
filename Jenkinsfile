pipleline{
  agent any
  parameters{
    string(name: 'HOSTNAME')
    string(name: 'dir')
  }
    stages {
    stage("build"){
      steps{
         build job: 'FileExplorer', parameters: [string(name: 'HOSTNAME', value: params.HOSTNAME), string(name: 'dir', value: params.dir)]
      }
    }
    
  }
}
