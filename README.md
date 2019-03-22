# How-to-create-custom-YUM-repository
How to create custom YUM repository

1. download repository rpms
  wget -m <web repo url>

2. Create repository database
  createrepo </path/to/repository>

3. Configure YUM repository

4. Check repolist and install some packages
  yum repolist
  yum install php-7

NEXT DEMO: Access the newly created YUM repository from remote hosts using http 
