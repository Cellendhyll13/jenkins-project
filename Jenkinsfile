node {
    stage('clone') { 
        git branch: 'main', credentialsId: '49c4d9a9-da43-4c36-af16-12ac8249f9ad', url: 'https://github.com/Cellendhyll13/jenkins-project.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
