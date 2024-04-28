# Virtualization Concepts and Tools for DevOps

1. `Hypervisor`: The software, firmware, or hardware that creates and manages virtual machines. There are two types:
   - **Type 1 (Bare-Metal)**: Runs directly on the system hardware. Examples include VMware ESXi, Microsoft Hyper-V, and Xen.
   - **Type 2 (Hosted)**: Runs on a host operating system that provides virtualization services, such as VMware Workstation and Oracle VirtualBox.

2. `VMware vSphere`: A server virtualization platform from VMware that provides a complete infrastructure for virtualizing and managing servers, networking, and storage in data centers.

3. `Microsoft Hyper-V`: A virtualization product from Microsoft, included with Windows Server, which allows system administrators to create and manage virtual machines.

4. `KVM (Kernel-based Virtual Machine)`: An open-source virtualization technology built into Linux, turning it into a hypervisor that can host multiple, isolated virtual environments.

5. `Oracle VirtualBox`: An open-source, cross-platform virtualization software that allows you to run multiple guest operating systems on a single host machine.

6. `Xen`: An open-source type-1 hypervisor, providing a powerful, efficient, and secure feature set for virtualization of x86, x86_64, IA64, ARM, and other CPU architectures.

7. `Containers`: Unlike virtual machines that virtualize a whole computer, containers virtualize just the operating system so that multiple workloads can run on a single OS instance. Docker and Kubernetes are prominent examples.

8. `Docker`: A platform designed to make it easier to create, deploy, and run applications by using containers.

9. `Kubernetes`: An open-source container-orchestration system for automating computer application deployment, scaling, and management.

10. `VMware NSX`: A network virtualization and security platform that enables the creation of entire networks in software and embeds them in the hypervisor layer.

11. `Software-Defined Networking (SDN)`: An approach to network management that allows dynamic, programmatically efficient network configuration, which helps to improve network performance and monitoring.

12. `OpenStack`: An open-source platform for cloud computing, mostly deployed as infrastructure-as-a-service (IaaS), whereby virtual servers and other resources are made available to customers.

13. `Vagrant`: A tool for building and managing virtual machine environments in a single workflow. It provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology.

14. `Proxmox VE`: A complete open-source platform for enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage, and networking functionality on a single platform.

15. `VMware Workstation`: A hosted hypervisor that runs on x64 versions of Windows and Linux operating systems; it enables users to set up virtual machines on a single physical machine, and use them simultaneously along with the actual machine.

16. `Paravirtualization`: A virtualization technique that presents a software interface to virtual machines that is similar but not identical to that of the underlying hardware.

17. `Virtual Desktop Infrastructure (VDI)`: A form of desktop virtualization that hosts desktop environments on a central server and deploys them to end-users on request.

18. `Storage Virtualization`: The pooling of physical storage from multiple network storage devices into what appears to be a single storage device managed from a central console.

19. `Network Function Virtualization (NFV)`: A network architecture concept that uses the technologies of IT virtualization to virtualize entire classes of network node functions into building blocks that may connect, or chain together, to create communication services.

20. `Citrix XenApp and XenDesktop`: Products that provide application and desktop virtualization services to deliver Windows applications and desktops to any device, while securing vital data.

## Additional Virtualization Concepts for DevOps

21. `Server Virtualization`: The partitioning of a physical server into smaller virtual servers to help maximize resource usage. It involves masking server resources, including the number and identity of individual physical servers, processors, and operating systems.

22. `Application Virtualization`: A process that allows applications to run in environments that do not suit the native application. Examples include Citrix application virtualization or Microsoft App-V, which abstract application layers from the OS, improving compatibility and manageability.

23. `Desktop as a Service (DaaS)`: A cloud computing offering that delivers virtual desktops provided by a third party to end-users over the Internet, billed on a subscription basis. Examples include VMware Horizon Cloud on Microsoft Azure and Citrix Managed Desktops.

24. `Hyperconverged Infrastructure (HCI)`: A software-defined IT infrastructure that virtualizes all the elements of conventional "hardware-defined" systems. HCI includes, at a minimum, virtualized computing (a hypervisor), a virtualized SAN (software-defined storage), and virtualized networking (software-defined networking).

25. `Software-Defined Data Center (SDDC)`: A data center where all infrastructure elements – networking, storage, CPU, and security – are virtualized and delivered as a service. VMware and OpenStack are leaders in the SDDC markets.

26. `Virtual Machine Escape`: A serious security concern that occurs when the code running on a VM breaks out and interacts directly with the hypervisor, potentially compromising the host operating system.

27. `Virtual Machine Migration`: Moving a virtual machine from one physical host to another while it is running, often using a tool such as VMware vMotion. This is used to conduct hardware maintenance without downtime or to balance loads.

28. `Network Virtualization`: The process of combining hardware and software network resources and network functionality into a single, software-based administrative entity, a virtual network.

29. `Cloud-Native Technologies`: Technologies that are used to develop applications built with services packaged in containers, deployed as microservices, and managed on elastic infrastructure through agile DevOps processes and continuous delivery workflows.

30. `Container Orchestration`: The automation of the management, scaling, and networking of containers. Kubernetes is currently the leader in this space, helping to deploy, scale, and manage containerized applications across clusters of servers.