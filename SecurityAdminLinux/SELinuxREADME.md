#Work for Module3 case study performed in Kali Linux virutual machine. It is the README file is below with answers to questions.














$ mkdir SELinux



$ cd SELinux



$ touch LinuxSecREADME.md



$ nano LinuxSecREADME.md



$







#The following will explain SELinux to Tom and Jane.


1. 
- SELinux (Security-Enhanced Linux) is the security policy that gives advanced access controls for Linux Systems. It is built on top of the Linux kernel and is a flexible, fine-grained security model to enforce security policies.


2. 

- For the basic architecture of SELinux, is comprised of three components which are the kernel, the userspace libraries and utilities, and the policy.
        - The kernel enforces security policy.

        - The userspace libraries and utilities hold the interface for managing the policy.

        - The policy is the set of rules that define what actions are allowed and denied.

3. 

- SELinux features:

        - Type enforcement = allows or denies access to the resources based on the type of subject (the process) and the type of object (the file).

        - Role-based access controls (RBAC) - assigns roles to the subjects and objects and manages the access on those roles.

        - Multi-level security = allows for different levels of security to be assigned to various different resources.

        - Policy language: allows for custom policies to be created and met.

        - Domain Type Enforcement (DTE): this allows for fine-grained control over access to resources by defining domains for processes and specifying allowed interactions between them.

        - Boolean settings: which allows for the enabling or disabling of specific SELinux features at runtime.

        - Auditing: which records all security-related events, such as access attempts, in the system logs for later analysis.



4. 
    SELinux is relevant for larger teams as it provides a way to enforce security policies consistently across all systems and users, and allows for the central management of access controls.

    Virtualization and containers are both technologies that allow for the isolation of resources, such as computing power, storage, and networks. However, they work in different ways.
    Virtualization creates a virtualized environment, such as a virtual machine, that runs on top of a host operating system. Containers, on the other hand, share the host operating system kernel and run isolated processes within the host.


5.  Linux hardening is the process of securing a Linux system by reducing its attack surface and strengthening its defenses against potential threats. This can include implementing security policies like SELinux, using firewalls, disabling unnecessary services and accounts, and applying software updates and patches.


AppArmor is another alternative to SELinux that provides access controls for Linux systems. It is similar to SELinux in that it uses a security policy to restrict the actions of processes, but it uses a simpler rule syntax and focuses on application-level security.









