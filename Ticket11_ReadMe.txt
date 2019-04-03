Made all the previous playbooks interactive.
Each playbook has a comments section on top, where it explains which variable should be given when prompted during a template launch on ansible tower

Example from route53.yaml:

# Please specify the following variables when prompted while launching the template   
# state: present | absent | get | create | delete 
# zone: The DNS zone to modify, e.g. example.com
# record: The full DNS record to create or delete e.g. tower.example.com
# type: A | CNAME | MX | AAAA | TXT | PTR | SRV | SPF | CAA | NS | SOA
# ttl: The TTL to give the new record
# value: The new value when creating a DNS record