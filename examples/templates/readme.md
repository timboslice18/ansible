Running the ios_parser.yml on Cisco IOS devices will send the output of certain commands to custom parsers and will result in 2 files being created:
   - hostvars/{{inventory_hostname}}/yml - contains host level facts/variables
   - groupvars/all.yml - Contains grouped facts/variables (snmp,ntp,etc.)

Running the switch_template.yml playbook will result in a configuration file being created based on the switch_template.j2 template
