 node {
           stage('buildImage'){
             openshiftBuild(buildConfig: 'php', showBuildLogs: 'true')
           }
           stage('deployApplication'){
             openshiftDeploy(deploymentConfig: 'php')
           }
         }
