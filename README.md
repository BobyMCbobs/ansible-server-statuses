# ansible-server-status
Get a status report on (a) Linux server(s).  

What does the report include?
- failed login count
- sucessful login count
- last 10 sucessful login
- server uptime
- kernel version information
- free space
- free space
- boot time
- the IP of which most failed logins come from

## Run
`ansible-playbook main.yml`  
