//git凭证Id
def git_auth = "548a903f-4731-4dff-9901-ce526b21c915"
//git的项目地址
def git_url = "https://github.com/honeyland414/Jenkins-demo.git"
//git拉取的分支
def git_branch="master"

node{
    stage('拉取代码'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '548a903f-4731-4dff-9901-ce526b21c915', url: 'https://github.com/honeyland414/Jenkins-demo.git']]])
    }
}
