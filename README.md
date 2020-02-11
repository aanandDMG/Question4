# goals101-Question4

Requirement 

Ansible

--------------------------------------------------------------------------------------------------------------------------------------------------
Details
--------------------------------------------------------------------------------------------------------------------------------------------------

The role named goals101 contains all the main.yaml files for all specific targets in respective folders like vars, handlers, tasks, default etc. 
Vars folder have main.yaml which contains all the variable that is required for the Playbook like user name, state, shell etc.
Kindly change the --hosts: value from tasks/main.yaml.
Once this playbook is run kindly verify users (docker kubernetes git aws ansible) in /etc/passwd file.

Please Run:

ansible-playbook goals101.yaml

Once the --hosts has been changed :)
