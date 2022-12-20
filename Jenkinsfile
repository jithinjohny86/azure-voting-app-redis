pipeline{
    agent any
    stages {
        stage ("Verify Git Branch through echo")
        {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        
        stage ("Print current WD")
        {
            steps {
                sh(script: 'echo print working directory')
                sh(script: 'pwd')
            }
        }
    }
}
