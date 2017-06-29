sudo yum-config-manager     --add-repo     https://download.docker.com/linux/centos/docker-ce.repo
sudo yum makecache fast

78  sudo yum install docker-ce docker-ce-selinux
   79  sudo yum install docker-ce-selinux
   80  sudo vi /etc/group
   82  sudo systemctl start docker.service
   83  sudo systemctl enable docker.service
   84  sudo systemctl status docker.service
   85  docker run  hello-world

sudo yum install docker-ce docker-ce-selinux.noarch
##   55  sudo yum install container-selinux
##   56  sudo rpm -qi
##   57  sudo rpm -qa
##   58  sudo rpm -qa | grep selinux
##   59  history

