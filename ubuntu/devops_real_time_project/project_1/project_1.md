# +++++ Project-1 +++++


### Pre-Requisites
1. Install Jenkins
1. Install Ansible
1. Install Apache Maven
1. Install Kubernetes Cluster
1. Git Account

<br/>

## +++++++++++++++++++++++++++ DAY 1 ++++++++++++++++++++++++++++

### Setup EC2 servers along with Github account.

<br/>

1. **[Install Jenkins & Ansible ](https://github.com/sunnydevops2022/DevOps/blob/master/ubuntu/devops_real_time_project/project_1/jenkins_ansible_installation_p1.md)**

1. **[Install Kubernetes Cluster](https://github.com/sunnydevops2022/DevOps/blob/master/ubuntu/devops_real_time_project/project_1/kubernetes_installation_p1.md)**

1. **[Git Account](https://github.com)**












<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

## `*************************   EOF   *************************`

### Configure Maven on Jenkins server
```
wget https://dlcdn.apache.org/maven/maven-3/3.9.1/binaries/apache-maven-3.9.1-bin.zip

vim ~/.bashrc

## Add end of the file & save it.
export M2_HOME=/opt/apache-maven-3.9.1
export PATH=$PATH:$M2_HOME/bin

source ~/.bashrc

mvn -version
```