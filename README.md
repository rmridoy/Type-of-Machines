1. State what the advantages of Virtual Machines are:
  - Virtual machines are fast to create and destroy. There is very little lead time between when one is requested and when the virtual machine is usable. Some systems can spin up a new virtual machine in less than a minute. Consequently, it is easy to create a virtual machine for a specific task and delete it when the task is completed which is called ephemeral machine.
  - Virtualization systems are programmable because their machines are controlled through software.
  - An API can be used to create, start, stop, modify, and destroy virtual machines. Software can be written to orchestrate these functions on a large scale. This is not possible with physical machines, which have to be racked, cabled, and configured via manual labor.
  - Virtual machines are allocated a fixed amount of disk space, memory, and CPU from the physical machine. The hard drive a VM sees actually may be a single large file on the physical machine. Disadvantages of Virtual Machines Some resources, such as CPU cores, are shared.
   - A virtual machine can detect CPU contention. In Linux and the Xen hyper-visor, this is called “steal time”: it is the amount of CPU time that your virtual machine is missing because it was allocated to other virtual machines.
2. State what the advantages of containers are:
  - A container is a group of processes running on an operating system that are isolated from other such groups of processes. Each container has an environment with its own process name space, network configuration, and other resources.
  - Each container has its own copy of the packages, shared libraries, and other supporting files that it requires. Two containers running on the same machine cannot have dependency or version conflicts.
  - Containers are very lightweight because they do not require an entire OS. Only the specific system files needed by the software are copied into the container. The system allocates disk space as files are needed, as opposed to allocating a large virtual disk ahead of time.
  - They are self-contained that’s why they eliminate dependencies and conflicts.
3. State when you might select physical machines over virtual machines:
  - Virtual machines have lot more advantages over physical machines in costs, efficiency, and lifespan but however physical machines have improved performances.
  - Physical machine will not affect other physical machines, but virtual machine will do that.
  - Physical machines are more predictable and reliable where virtual machines will run a operating system which will take up a lot of memory and space. Also, physical machines are safer, so they are less likely to get attack by hacker than a virtual machine.
