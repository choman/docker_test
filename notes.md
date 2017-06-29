# Docker Notes

Following the docker install guide for centos

NOTE: Unable to install pre-reqs with subscription
NOTE: 7.2 has cert issue which requires a local
      copy of docker-ce
NOTE: 7.2 has sig issue with docker.rpm
NOTE: unofficial reference says docker-ce is for rhel 7.3+

## 7.2 Server (needs verification)
   - Server w/ GUI + Dev Tools
   - vbox additions 
   - reboot
   - register && subscribe to correct pool
   - subscript to additional repos
   - yum install container-selinux
   - install local copy of docker-ce
   - modify /etc/group
   - start and enable docker
   - reboot
   - docker run hello-world

## 7.2 Workstation (99% verified)
   - following centos guide
   - vbox additions
   - modify /etc/group
   - reboot
   - register && subscribe to correct pool
   - install LOCAL copy of container-selinux
   - install LOCAL copy of docker-ce
   - modify /etc/group
   - start and enable docker
   - reboot
   - docker run hello-world

## 7.3 Server
   - Server w/ GUI + Dev Tools
   - added 3 repos,  this gets container-selinux????

## 7.3 Workstation
   - may need selinux-policy selinux-policy-targeted
   - need policycoreutils
      - unsure if extra repros are needed
   - need container-selinux rpm

## 7.4 Beta Server
   - Server w/ GUI + Dev Tools
   - added 3 repos,  this gets container-selinux????

# AppImage Notes
  - Had to install libXscreensaver (sp)






