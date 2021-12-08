## CI/CD


CI and CD stand for continuous integration and continuous delivery/continuous deployment. In very simple terms, CI is a modern
software development practice in which incremental code changes are made frequently and reliably. Automated build-and-test steps 
triggered by CI ensure that code changes being merged into the repository are reliable. The code is then delivered quickly and 
seamlessly as a part of the CD process. In the software world, the CI/CD pipeline refers to the automation that enables 
incremental code changes from developers’ desktops to be delivered quickly and reliably to production.


## DevOps
DevOps stands for Development and Operations. It is a software engineering practice that focuses on bringing together the development team and the operations team for the purpose of automating the project at every stage. This approach helps in easily automating the project service management in order to aid the objectives at the operational level and improve the understanding of the technological stack used in the production environment.

This way of practice is related to agile methodology and it mainly focuses on team communication, resource management, and teamwork. The main benefits of following this structure are the speed of development and resolving the issues at the production environment level, the stability of applications, and the innovation involved behind it.


## Docker

The Docker technology provides you the third option with a concept known as “Containerization”. Let’s try to comprehend this term by comparing it with Virtualization. Both of these help you in deploying applications inside environments that are isolated from the underlying hardware. The chief difference is the level of isolation.
Virtualization enables the creation of Virtual Machines(VM) from the underlying hardware through Hypervisor. You can think of Hypervisor as a Virtual Machine Monitor that creates and manages virtual machines. However, each VM contains the Operating System(OS) layer(which you as a user have to manage). This makes the VM heavyweight(Imagine a VM of size 1 GB to deploy an application of size, just about 300 MB)
Containerization mitigates this issue with containers. A Container is a package that constitutes an application with all of the parts it needs such as libraries and dependencies. Instead of hosting each OS per application, another layer called a “Container Engine” is added between the OS and the applications. This allows the OS to be shared amongst all the containers. As a consequence of containers not needing to embed a full OS, they are very lightweight, commonly around 5–100 MB.
