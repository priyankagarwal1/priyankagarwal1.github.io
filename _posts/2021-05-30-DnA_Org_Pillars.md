# Data Analytics Organization Pillars


![One of its kind scenery from Pangong Lake, Leh](images/01Leh.png) 


A lot of people get confused with the evolving designations and their role in Data Analytics. Let me try to give more perspective on it (based on experience and research from internet). Before that, let us understand how the Data Analytics team is typically organized in a medium-to-large scale enterprise. This will then be easy to connect the dots.
Data Engineering, Data Platform and Data Analytics are three important pillars of department. There can be many splits/customizations and associations with other departments but primarily these 3 cover most of it. Primarily, other departments are Product Management, Data Management, Program Management, Security & Compliance, other software development teams. All 3 teams interact with Product Management team or Business teams. Let’s quickly look into the primary responsibilities for these Pillar Teams.


## Data Engineering
Data pipes from multiple sources feeding into a large reservoir that further feeds to multiple consumers. This system shall be fast, reliable, easy to operate, cost effective, architecturally sound and secure meant to serve its users. Typical role of Data Engineer is to perform the below tasks in this team.
a.	Conceptualizing & Managing Data Lake (for all type of data like Text, Numerical, Images, etc)
b.	Manage input data from multiple sources and how it flows into on-prem/cloud databases
c.	How and who shall consume data from data lake. Manage security and access policies.

## Data Platform
Managing all hardware and software in Data Analytics team (procurement, commissioning, upgrades, decommissioning, trainings, firewalls etc). There is high interest towards moving on-prem solutions to cloud-based infrastructure; this implies that this team is also managing these migrations (software platform & hardware platform). These include all softwares used by Data Engineers, Data Analysts and Data Scientists. On the performance improvement side, this team constantly works towards reducing downtime, managing data peaks/outages, upgrades/patches, reducing platform failures, software deployments (CI/CD from development environment to production environment) and continuous gaze on technological advancements.

## Data Analytics
This team is consuming data for multiple purposes like standard dashboards, data feeds, data dumps, self-service tools, machine learning models for predicting future or trying to understand relationship between input and output etc. Data Analysts in this team will extract data and prepare dashboards, create useful insights for easy consumption for business reviews and connect business logic after data wrangling.
Some teams have Visualization Engineers who can make charming dashboards on visualization tool of choice and directly connecting them from databases.
Also there are Data Scientists, who are preferably from maths or statistics background whose role is to work on advanced data science techniques to be able to train and deploy machine learning models that can predict things or interpret text to classify, in general to solve business problem using Python/R etc. Data Scientists are not expected to know about business processes and therefore they work closely with Data Analysts and sometimes with business team SME.
A general rule of thumb is, ~80% of problems can be resolved by simpler techniques like basic data analysis, rest needs advanced techniques (optimization problems, text/image classification, forecasting etc).
