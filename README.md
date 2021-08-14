# auto-provisioning-elk-stack-with-ci-cd
Automated Provisioning of ELK stack using ansible, docker and jenkins.


mkdir auto-provisioning-elk-stack-ci-cd
cd auto-provisioning-elk-stack-ci-cd
create a site.yml file
mkdir roles
cd roles
ansible-galaxy init jenkins

++ in jenkins file
We have included all the jenkins tasks here. Starting with downloading java, setting the correct java version, downloading jenkins, importing GPG key, installing and configuring Jenkins and finally starting the jenkins service and enabling it to start on reboot.