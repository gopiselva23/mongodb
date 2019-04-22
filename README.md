
Running ansible
-------------------

    $ ansible -i inventory <pattern> -m <module> [options] [-a <arguments>]
    
    $ ansible-playbook -i "10.xx.xx.xx," mainrole.yml -e"ROLE=<role-name>" -u username -k 


