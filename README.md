# Unified-CloudWatch-Agent

The idea with this Unified-CloudWatch-Agent is that the configuration itself is stored into Parameter Store and can be changed, obviously whenever we want. And all the instances may be using EC2 user data would simply fetch this configuration directly from SSM and use this to configure the unified logs agents,which is something that is a little bit easier to do than just going to go ahead and configureing this file to be appearing on your instance magically every single time. 
