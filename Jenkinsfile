pipeline {
    agent any

    stages{
        stage("checkout code") {
           //checkout repository 
           steps {
            git branch: 'main', url: 'https://github.com/JekaterinaAksjonova/JenkinsSeleniumIDE'
           }
        }
        stage("Set up .NET Core") {
            //install dotnet
        }
        stage("Restore dependencies") {
            //install dependencies
        }
        stage("Buld") {
            //build
        }
        stage("Run tests") {
           //run tests 
        }
    }
}