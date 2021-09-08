# SRE Github SSH Setup

## Steps to Create a SSH link with Github
- First create a key with `ssh-keygen -t rsa -b 4096 -C "email@linked.com"`
- Then copy the contents of the `id_rsa.pub` which was created
- Head over to github and click your account in the top right `settings>SSHkeys`
- Once this has been saved, create a new repository
- click `code` and use the `SSH` which should look like `git@github.com:githubaccount/repoid.git`



