node {
    stage('Clone') {
        git 'https://github.com/Gyles75/hello-world-devops.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Application.java'
    }
    stage('Run') {
        sh label: '', script: 'java Application'
    }
}
