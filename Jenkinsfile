node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/aymendr/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Test') {
        sh 'java Main'
    }
}
