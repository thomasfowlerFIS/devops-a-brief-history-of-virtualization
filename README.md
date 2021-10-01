# **A Brief History of Virtualization**

Course: DevOps

Mod: Week 1

Topic: Virtualization

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Summary:**

Virtualizatiion has gone through many evolutionary changes
over the years, and with these advancements in tooling and
strategy, virtualization and virtual machines have become a
commodity in the world of DevOps and DevSecOps. By the end of
this lesson you will be able to:

------------------------------------------------

### **Learning Goals:**

* Explain virtualization, its history, and its importance in
the field of DevOps/DevSecOps.

* Diagram the model of virtualization using a hypervisor and
virtual machines.

* Understand the benefits and tradeoffs of virtualization and  
their impact on DevOps.

------------------------------------------------

### **A Brief History on Application Support**

From the mid to late 1990's to the early 2000's, when the internet was
first coming into the mainstream in business and software development,
web applications became popular due to their accessability and
interoperability with other web applications. These conditions were
the precursors to the ubiquity of web-based APIs that software
developers, platform engineers, and DevOps engineers use today.

To deploy these web applications was very costly and time consuming.
This was due to several factors, but the list includes but is not
limited to the following (in no particular order):

* Physical server procurement and provisioning

* Network configuration and integration of the server

* Securing and granting access to servers

Effectively, a systems administrator or similarly functioning role,
would need to acquire and provision a physical server. Next, the
systems administrator would coordinate with the network administrator
to ensure proper addition and membership to the network/LAN. The
systems administrator would then secure access to the server, and
finally another list of subsequent tasks were performed to enable
the web application to be deployed.

While very costly, this process was unfortunately very necessary.
Worse still, the system administrators needed to isolate these
servers and their applications from one another. Even when isolation
was successful, one application could bring down an entire server and
all the other applications it hosted, further compounding the issue.
They needed a solution that would allow for some level of
customization when provisioning servers, while reducing or
eliminating the overhead of installing hardware, configuring
networks, installing operating systems, etc.

------------------------------------------------

### **Why Virtualization?**

To combat these issues and to streamline the provisioning
of infrastructure to support applications, virtualization was
introduced as a solution. The rationale was to emulate hardware in
software to eliminate the ramp-up time necessary to provision
physical servers/machines and allow for a catalog of virtual machine
images from which application teams could select for their specific
needs.

These virtual machine images allowed the system administrators
to support application teams with multiple operating systems,
baked-in software packages and dependencies, a limited degree of
application isolation, etc. This reduced the time to deployment for
application teams and allowed them to shift more of their focus
toward feature development.

This was approaching the self-service the system administrators
wanted for application teams to become more self-sufficient.
Providing more self-service capabilities allowed the system
administrators to focus more on hardening their infrastructure and
securing their networks.

------------------------------------------------

### **What Does Virtualization Do?**

Virtualization using virtual machines exists using the following
hierarchy:

* Utilizes existing hardware and infrastructure for the
virtualization host.
* Leverages the host operating system to run the virtualization
runtime.
* Employs the use of an application or software called a hypervisor
to manage all instances of virtual machines running in the
virtualization runtime.
* Each virtual machine instance has its own guest operating system
with its own configuration and dependencies.
* Applications are installed on the guest operating system on the
virtual machine.

<!-- Need figure here -->
<!-- [Insert Figure - TBD] -->

------------------------------------------------

### **Lab Excercise 1**

* Deploy an Ubuntu virtual machine using VirtualBox

* Install an application that listens for requests

* Configure the virtual machine to allow external traffic

------------------------------------------------
