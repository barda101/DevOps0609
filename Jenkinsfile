properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'master', url: 'https://github.com/barda101/DevOps0609.git'
    }
    stage("execute") {
        sh "python3 2.py"
    }
}