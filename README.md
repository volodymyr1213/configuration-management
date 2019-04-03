# Ansible Tower

* The follow documentation will update everything in your host including kernel.
* You will be using AWX/Ansible to do full update

######## Warning, currently this playbook is only supporting Centos. Use it at your own risk #########

1. On your AWX specify branch to "Team_C"  

2. Specify the variable hostname under "Extra Variables"

3. On your template be sure to select "patching.yml" and celect "PROMPT ON LAUNCH"

4. RUN your template job and hope for the best!
