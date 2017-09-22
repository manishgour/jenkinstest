pipeline {
    agent { docker 'maven:3.3.3' }
    def toolbelt = tool 'toolbelt'
    
    stages {
        stage('build') {
            steps {
                bat '${toolbelt} force --help'
                bat '${toolbelt} force:alias --help'
            }
        }
    }
}
