node {
    stage('clone') {
        git 'https://github.com/GauthierMagne/testJenkins.git'
    }
    stage('Build') {
         sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
