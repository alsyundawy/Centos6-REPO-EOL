# Centos6-REPO-EOL
CentOS 6 Repository EOL


CentOS 6 Repository EOL

curl https://raw.githubusercontent.com/alsyundawy/Centos6-REPO-EOL/main/CentOS-Base.repo --output /etc/yum.repos.d/CentOS-Base.repo

curl https://raw.githubusercontent.com/alsyundawy/Centos6-REPO-EOL/main/epel.repo --output /etc/yum.repos.d/epel.repo

yum -y install centos-release-scl

curl https://raw.githubusercontent.com/alsyundawy/Centos6-REPO-EOL/main/CentOS-SCLo-scl.repo --output /etc/yum.repos.d/CentOS-SCLo-scl.repo

curl https://raw.githubusercontent.com/alsyundawy/Centos6-REPO-EOL/main/CentOS-SCLo-scl-rh.repo --output /etc/yum.repos.d/CentOS-SCLo-scl-rh.repo
