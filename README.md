# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## PROGRAM:
# CLIENT:

![image](https://github.com/danushreddy7/4.Execution_of_NetworkCommends/assets/149035740/c47c28ea-0ae3-4009-87a7-7940ccb6acff)

# SERVER:

![image](https://github.com/danushreddy7/4.Execution_of_NetworkCommends/assets/149035740/e40cdd49-26fb-4131-8271-186cfe4e13b2)

# TRACER:
from scapy.all import* 
target = ["www.google.com"] 
result, unans = traceroute(target,maxttl=32) 
print(result,unans) 


## Output:
# CLIENT:

![image](https://github.com/danushreddy7/4.Execution_of_NetworkCommends/assets/149035740/6e371f58-e818-4500-b5e6-fbd0d53a0f10)

# SERVER:

![image](https://github.com/danushreddy7/4.Execution_of_NetworkCommends/assets/149035740/4691644d-78b8-4ee8-a925-d85c6069b4b7)

## Result
Thus Execution of Network commands Performed 
