pipeline {
    agent none
    stages
    {
    stage('Checkout') {
        step
        {
        git credentialsId: "RTID_BOT_USER_BASIC", url: 'https://github.com/samsysengg/simple-java-maven-app.git', branch: 'master'
        }  
        }
    stage('Listing files') {
        step
        {
                        sh 'ls'
        }
        }
}
}
