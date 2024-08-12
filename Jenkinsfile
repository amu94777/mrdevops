pipeline {
     agent any 
     stages {
        stage ('git checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/amu94777/mrdevops_java_app.git'
                }
            }
        }
     }

     }
}