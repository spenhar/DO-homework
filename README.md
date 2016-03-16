#### Challenge 2
DigitalOcean users need a way to compare graphs from several different droplets in order to troubleshoot whether an issue is affecting a single droplet or more. Currently, we only allow users to see graphs for each droplet separately.

How and where might we create an interface that allows users to keep track of important metrics across their many droplets?

--- 

---
# How

To keep track of metrics across many droplets there are two solutions:
1. Select multiple droplets to compare
2. Grouping

View All Droplet Activity
View selected droplet activity

Operating under the assumption that the most common use case for viewing multiple droplet metrics is because you have an app with multiple droplets working together. 

---
# Where
The 'Droplets' view is the primary view when logged into the app, I think this would be a great place to give an at-a-glance status of your servers. Especially helpful when you can see what the status of your cluster is. 

---
### The current 'Droplets' view:
<img width="1156" alt="2-droplets" src="https://cloud.githubusercontent.com/assets/6846053/13792911/ac97a42a-eaca-11e5-931f-5363c3130819.png">
---
### A mockup of what a 'Group' might look like:
*note* a high-level snapshot of cluster performance status
![2-droplets-group-mockup](https://cloud.githubusercontent.com/assets/6846053/13792910/ac953122-eaca-11e5-8ed4-902a76d5cdd0.jpg)

---
## Drill Down
A user wants to drill past the top-level status message and monitor the state of multiple droplets, so they click through and see some kind of compound graph or monitoring system similar to your internal team or the sketch below:
<img src="https://cloud.githubusercontent.com/assets/6846053/13792917/acb1f44c-eaca-11e5-9147-55feacdfbba2.jpg">
<img src="https://cloud.githubusercontent.com/assets/6846053/13800487/0fb27906-eb00-11e5-845d-9894f241a59f.jpg">
* The second drawing shows 4 different line-graphs stacked, with the most pressing concern in front.
* A information card telling the user the most relevant concern with a actionable button to solve to problem "Upgrade GPU stat!"
* There is a clear 'Danger Zone' which also allows someone to quickly see when their performance stats are getting in to too-hott territory. 

I imagine this graph view displaying multiple droplet performance information is a great time to sell a customer on an upgrade. In my thinking through this problem, I couldn't help but return back to how important messaging and notification must be for DO. Putting myself in the shoes of a frequent D.O. user, I'd likely not be monitoring all the time, but would want to know immediately if my server was reaching the upper limits of it's capabilities so I could have time to upgrade before it failed. Alternately, I was brainstorming an option of having a premium droplet option that was 'stretchy' so as to accommodate for any surges in performance needs - a pay-what-is-used model for those who want to set it and forget it.

Clearly I am limited in my knowledge of D.O. business strategy and user behaviors, so my thoughts are almost entirely built on conjecture from using the product a few times to test and accomplish this assignment.

--- 
## Additional Ideas
When your droplets are processing and the user is waiting for status bars to show that set-up is complete, there is an opportunity to do something: why not ask if they want these droplets to be grouped?
<img src="https://cloud.githubusercontent.com/assets/6846053/13792919/acb76f58-eaca-11e5-98eb-2b74134bf05c.jpg">

