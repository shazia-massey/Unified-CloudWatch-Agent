# Unified-CloudWatch-Agent

The idea with this Unified-CloudWatch-Agent is that the configuration itself is stored into Parameter Store and can be changed, obviously whenever we want. And all the instances may be using EC2 user data would simply fetch this configuration directly from SSM and use this to configure the unified logs agents,which is something that is a little bit easier to do than just going to go ahead and configureing this file to be appearing on your instance magically every single time. Finally, we can collect metrics by CloudWatch-Agent CPU_time_active,Disk_free,Disk_used_percent,Men_active,men_available,net_packets_sent,Processes_dead,Swap_free,Swap_used, 
