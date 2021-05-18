pipeline {
agent any
stages {
            stage('Initial checks') {
                steps {
                    sh '''
                        echo "
                          BRANCH_NAME = $BRANCH_NAME
                          CHANGE_BRANCH = $CHANGE_BRANCH
                          CHANGE_TARGET = $CHANGE_TARGET
                          TAG_SUFFIX = $TAG_SUFFIX
                          VERSION = $VERSION
                          COMMITID = $commitId
                        "
                        '''
                } }
}
