# DO-homework
---
### Challenge 2
DigitalOcean users need a way to compare graphs from several different droplets in order to troubleshoot whether an issue is affecting a single droplet or more. Currently, we only allow users to see graphs for each droplet separately.
How and where might we create an interface that allows users to keep track of important metrics across their many droplets?
--- 
### Define Problem
Q: What problem are we solving?
A: Currently, a user can only see a graph for each droplet individually. A user should be able to compare graphs in order to troubleshoot an issue and view status across their droplets.

Q: What is the proposed solution?
A: Graphs are part of the answer, but I’m arguing that the user really needs to be notified when there’s an emergency or a potential problem. Viewing/comparing graphs is secondary to the primary need. 

Though the problem is found a few steps down the users experience (after they’ve built droplets and are using them to the point of needing to monitor their activity), I believe we can help the issue by ‘grouping’ droplets early on, and then viewing those droplets in their groups. 

Encouraging the user to group their droplets while they’re setting up, helps us start the process. DO would also need to provide support to add, remove, modify groups later on. 

Without knowing much about the average Digital Ocean user, I have to assume that most people just want to know when there’s a problem. Instead of 

The droplets page
Without having to drill down deeper, it’d be nice to get a snapshot status of your droplets or group of droplets. 
