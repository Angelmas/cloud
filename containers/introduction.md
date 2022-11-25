


- What is a Docker?

Docker is primarily a container runtime.It's a piece of software the is designed to implement and support containers.
Docker allows you to run container systems and offers tools for creating and managing container images

- What is Kubernetes? 

is a container Orchestration tool
It allows you to easily build and manage your container infrastructure and automation.
Self-healing applications, automated scaling and deployments


Zero-Downtime Deployments

In the old days, deployments went like this

1) Take the server down for maintenance ( it is unavailable to customers)
2) Perform the deployment
3) Bring the server back up

A zero-downtime deployment (with containers)

1) Spin up containers running the new code
2) When they are fully up, direct user traffic to the new containers
3) Remove the old containers running the old code. No downtime for users!

Use cases 

Software portability: Running software in different machines
Isolation: Keeping individual pieces of software separated from one another
Scaling - Increasing or decreasing resources allocated to software as need
Automation: Aumating processes to save time and mony
Right use of Resorces: Faster, smaller and lighweight than VM

- Microservices:

Are a type of application architecture that involves splitting the application into a series of small independent services.

Microservices can be built, modify and scale separately with little impact on another
Reducing the possibility to crash and affect the entire application,
allows to use many technologies, not limited to one


- Automated Scaling:

Rferes to automatically provisioning resources in response to real time metrics.

You can automatically detect or prevent (or event predict) increase in usage

Wuthout Automated Scalinh, you must provision enough resources to conver your  poeak needs at all time

Before: If I need 10 servers to handle my peak ussage time, then I need 10 server all the time

- Containuous Deployment: Its the practice of deployiing new code automatically and frecueny

Insted of writing new code for months and doing a a big deployment. CD, means constantly doing many 
small deployments containing a large number of changes.


To mainting stability. while doing deplyment is important to make use of automation to ensure that deployments and stable  and consistent


- Automation pipeline:

For continuous delivery can automatically build a container image with the new code, test it, then automatically ship that same container image

- Self healing Application: applications that are able to automatically detect when something is broken
and take right actions


- Depeloper visibility: Developers and other have the ability to test the cide abd see exactly how it will behave in production.


# Containers in the cloud
Cloud : someone else's computer.
Being in thge cloud means that your are running software in a remote datacenter over the internet
