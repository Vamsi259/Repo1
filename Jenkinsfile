def workspace
node{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/sivajavatechie/JenkinsWar.git']]])
        workspace =pwd()
    }
    stage('complie')
    {
        echo "Compiling the code here"
    }
    stage('Unit Testing')
    {
        echo "Running Junit Test cases here"
    }
    stage('Installing')
    {
        echo "Installing the code here"
    }
    stage ('Deployment')
    {
        echo "Deploying"
    }
}
