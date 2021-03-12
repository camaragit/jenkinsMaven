node {
    stage('cloneGit') {
        git 'https://github.com/camaragit/jenkinsMaven.git'

    }
    stage('package') {
        sh 'mvn clean package'

    }
        stage('runjar') {
        sh 'java -jar target/jenkinsMaven.jar'

    }

}