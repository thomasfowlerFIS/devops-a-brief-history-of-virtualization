# **A Brief History of Virtualization**

Course: DevOps
Mod: Week 1
Topic: Virtualization
Amount of time: 1.5 hours
Author: Thomas Fowler

## **Lesson Summary:**

Virtualizatiion has gone through many evolutionary changes
over the years, and with these advancements in tooling and
strategy, virtualized machines have become a commodity in the
world of DevOps/DevSecOps. By the end of this lesson you will
be able to:

------------------------------------------------

### **Learning Goals:**

* Explain virtualization, its history, and its importance in
the field of DevOps/DevSecOps.
* Diagram the model of virtualization using a hypervisor and
virtual machines.
* Demonstrate provisioning and deprovisioning a virtual
machine.

------------------------------------------------

### **A Brief History on Application Support**

In the past, when system administrators needed to support
development efforts by application teams, they
would provision hardware to support those applications. This
was a very costly and resource intensive process and created
a significant amount of friction when deploying the
applications the system administrators were charged to support.

In order to provision the servers for these applications, the
system administrator would need to enter a service ticket for
the procurement of the machine or server, another ticket to make
sure the machine had network access, and potentially a host of
others including, but not limited to firewall configuration,
backup and recovery,software packages and dependencies, network
storage, etc., etc.

This process was costly and unfortunately very necessary to
support these applications. Worse still, the system
administrators needed to isolate these servers and their
applications from one another, further compounding the issue.
They needed a solution that would allow for some level of
customization when provisioning servers, while reducing or
eliminating the overhead of installing hardware, configuring
networks, installing operating systems, etc.

------------------------------------------------

### **Why Virtualization?**

To combat these issues and to streamline the provisioning
of infrastructure to support applications, virtualization was
introduced as a solution. The idea was to emulate hardware in
software to eliminate the physical ramp-up time necessary to
provision servers/machines and allow for a catalog of virtual machine
images from which application teams could select for their specific
needs. These virtual machine images allowed the system administrators
to provide multiple operating systems, baked-in software packages and
dependencies, a limited degree of application isolation, etc.

This was approaching the self-service the system administrators
wanted for application teams to become more self-sufficient.
Additionally, it allowed the system administrators to focus more
on hardening their infrastructure and securing their networks.

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

[Insert Figure - TBD]
<!-- Need figure here -->
<!-- ![The San Juan Mountains are beautiful!](https://mdg.imgix.net/assets/images/san-juan-mountains.jpg?auto=format&fit=clip&q=40&w=1080 "San Juan Mountains") -->

<!-- Just demoing a linked image here -->
<!-- [![An old rock in the desert](https://mdg.imgix.net/assets/images/shiprock.jpg?auto=format&fit=clip&q=40&w=1080 "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv) -->

------------------------------------------------

### **Lab Excercise 1**

* Deploy a virtual machine using VirtualBox

------------------------------------------------

### **Lab Excercise 2**

* Deploy multiple virtual machines using VirtualBox.
* Install applications to each virtual machine.
* Configure applications on each virtual machine
to communicate with the other.

------------------------------------------------

### **Quiz 1**

* TBD
* TBD
* TBD
* TBD
* TBD

------------------------------------------------