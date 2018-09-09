pipeline {
    agent any
    stages {
        stage('Example') {
            steps {checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '4ea65d99-98f8-43ed-b329-586ebff6cdd0', url: 'https://github.com/hadainn/google-hub.git']]])

                echo 'Hello World'
            
          }
          
            
        }
        
    }
}
changes
