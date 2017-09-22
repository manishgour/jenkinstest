pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                rmsg = bat 'sfdx force --help'
                println(rmsg)
            }
        }
    }
}
