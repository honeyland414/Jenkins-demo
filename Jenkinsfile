//git凭证Id
def git_auth = "2283a934-9e55-422d-a39e-9ce93ed2ff37"
//git的项目地址
def git_url = "https://github.com/honeyland414/Jenkins-demo.git"
//git拉取的分支
def git_branch="master"

node{
    stage('拉取代码'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '2283a934-9e55-422d-a39e-9ce93ed2ff37', url: 'https://github.com/honeyland414/Jenkins-demo.git']]])
    }
}
