node() {
    stage ("OUT"){
    deleteDir()
    git  "https://github.com/aDovbiy/test.git"
    }
    stage ("BUILD"){
    sh "echo Building ${BUILD_ID} build id"
    sh "echo Testing on ${NODE_NAME}"
    sh "echo Pulling on repo"
    }
}  
