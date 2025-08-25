node {
    stage('Clone') {
         git 'https://github.com/aminekbennani/jenkins-helloworld.git'
     }
    stage('Build') {
         sh '''javac Main.java
'''
     }
    stage('Run') {
        sh '''java Main
'''
     }
}
