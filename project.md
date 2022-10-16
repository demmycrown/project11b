## H2 Ansible – Automate Project

1. Install ansible

`sudo apt update`

`sudo apt install ansible`

2. Configure Jenkins build job to save your repository
3. Test your setup by making some change in README.MD file in master branch and make sure that builds starts automatically and Jenkins saves the files (build artifacts) in following folder

`ls /var/lib/jenkins/jobs/ansible/builds/<build_number>/archive/`
 
 - Create Github account and clone

 - Set up an Ansible Inventory

`ssh -A ubuntu@public-ip`

- Create a common playbooks

- Commit code to Github

`git status`

`git add <selected files>`

`git commit -m "commit message"`

`git push`

- Run first ansible test

`ansible-playbook -i inventory/dev.yml playbooks/common.yml`


