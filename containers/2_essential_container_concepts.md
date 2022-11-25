1970: Mainframe computers were a scarce resource for business due to cost. This leads the way to the delopment of centraliced computers and sharing resources.


Appeared Chroot -> Stand for Changes ROOT

With is 
Root/ 
 bin/
 etc/
 usr/
 var/
 home/
   Ell
   Spotz
   chroot/
     bin/
     etc/
     usr/
     var/
     home/
       Chat/
       Terry/
       Stosh/

 cgroups vs namespaces

cgrpups limits the access
namespace limits what you can see
there are currently six linux namespaces, although some consider cgroups to be the seventh

User, 
IPC: offers a way for multiple processes to exchange data by creating separate message queues for each namespace.
UTS: The UTS namespace allow the isolation of the hostname for each container.
PID: isolates a process ID from other namespaces, 
Mount: namespace controls the filesystem mount points that are visible to each container
Network


Chroot
Linux Namespaces
Network Namespace example


Control Groups: Cgroups, Isolate a proccesses ability to be able to have access to a resources,
A control group is a Linux Kernel Feature that limits and isolates the resouce usage of a collection of processes

Control groups:
blkio
cpu
The device subsystem allows you to pin groups of process to one CPU or to groups of process.
cpucct
cpuset
devices
The devices  subsystem allows or denies access to devices by tasks in a cgroup; controlling what the group of process can do on the device nodes including read and write.

freezer
The device subsystem suspends or resumes tasks in a cgroup.
memory
net_cls
net_prio



LAB:


Create a directory named /home/elba

Create a new user called napoleon.

Create the bin and lib64 directories in /home/elba

Copy /bin/bash into /home/elba/bin/bash.

Copy /bin/ls in to /home/elba/bin/ls

Copy /bin/cat in to /home/elba/bin/cat

Copy the libraries needed for bash, ls, and cat over to /home/elba/lib64.

Create the waterloo.txt file in the /home/elba directory

Create a chrooted environment in /home/elba with a bash shell.

Confirm commands work.

View the contents of waterloo.txt and find out how to escape your environment.

