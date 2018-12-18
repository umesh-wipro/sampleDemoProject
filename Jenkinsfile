node{
    
    stage ('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/umesh-wipro/sampleDemoProject.git']]])

    }
    stage('build')
    {
        echo('build the code');
        
    }
    stage('Analysis')
    {
        echo ('Analyse the code');        
    }
}
