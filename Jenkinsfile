 node {
           stage('buildImage'){
             openshiftBuild(buildConfig: 'php70', showBuildLogs: 'true')
           }
           stage('deployApplication'){
             openshiftDeploy(deploymentConfig: 'php70')
           }
         }
