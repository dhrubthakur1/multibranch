pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo "Test... ${BRANCH_NAME}   ${BUILD_NUMBER}  ${JOB_NAME}   ${env.BRANCH_IS_PRIMARY}"
            }
        }
    }
}
