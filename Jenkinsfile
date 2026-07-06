node {
    stage('git-clone') { 
        git branch: 'main', url: 'https://github.com/dontulasharanya/spring-petclinic.git'
    }
    stage('Build') {
      sh 'mvn package' 
    
    }
}
