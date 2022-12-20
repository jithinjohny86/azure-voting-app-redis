pipeline{
    agent any
    stages {
        stage ("Verify Git Branch through echo")
        {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage ("Print a simple sh command")
        {
            steps {
                sh(script: 'echo hello from sh')
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
