---
### Challenge 2
DigitalOcean users need a way to compare graphs from several different droplets in order to troubleshoot whether an issue is affecting a single droplet or more. Currently, we only allow users to see graphs for each droplet separately.

How and where might we create an interface that allows users to keep track of important metrics across their many droplets?

--- 
To keep track of metrics across many droplets there are two solutions:
1. Select multiple droplets to compare
2. Grouping

View All Droplet Activity
View selected droplet activity

Operating under the assumption that the most common use case for viewing multiple droplet metrics is because you have an app with multiple droplets working together. 


The current 'Droplets' view:
<img width="1156" alt="2-droplets" src="https://cloud.githubusercontent.com/assets/6846053/13792911/ac97a42a-eaca-11e5-931f-5363c3130819.png">

A mockup of what it might look like to have a group, including a high-level snapshot of performance status:
![2-droplets-group-mockup](https://cloud.githubusercontent.com/assets/6846053/13792910/ac953122-eaca-11e5-8ed4-902a76d5cdd0.jpg)
