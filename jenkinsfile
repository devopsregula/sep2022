node {
    stage('git clone') { 
    git branch: 'main', credentialsId: '2f17f227-4e75-4563-aac4-cf00290d95f3', url: 'https://github.com/devopsregula/sep2022.git'
    }
    stage('maven clean') {
       sh '''mvn clean'''
    }
    stage('maven validate') {
       sh '''mvn validate'''
    }
}
