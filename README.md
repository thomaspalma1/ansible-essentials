<div align="center">
   <h1 align="center"><b>Ansible Essentials</b></h1>
   <p align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ansible/ansible-original.svg" width="50"  height="50" />
   </p>
</div>

### About the project 📘

This repository presents a collection of infrastructure automation examples using Ansible, a widely adopted tool for configuration management and orchestration. The goal of the project is to explore essential automation concepts, such as playbook organization, the use of inventories and variables, as well as the execution of tasks and roles to configure and manage systems.

The content serves as a reference for simple environments and controlled experimentation, supporting hands-on learning and practical understanding of how to automate provisioning steps, enforce desired states, and manage infrastructure in a consistent and repeatable way.

It is important to note that the directory structure used in this repository does not represent a production-ready standard. Production environments require a more robust organization, including proper role separation, environment-specific inventories, secure variable handling, and adherence to best practices.

The focus of this repository is exclusively on personal study and learning.

---

### Usage ⚙️

To use the code in this repository, first clone the project to your machine using `git clone`. Then, navigate to the `playbooks/` directory, which contains all the automation examples.

Inside the `playbooks/` directory, you will find **multiple standalone playbooks**, each focused on a specific task or configuration commonly performed on **Linux systems**. Instead of a deeply modular structure with roles, this repository follows a simpler and more direct approach, where each file represents a practical automation scenario.

These playbooks cover operations such as:

* Package installation and updates;
* Service configuration and management;
* Basic system provisioning tasks;
* Execution of commands and file manipulation on Linux hosts.

This structure makes it easier to understand Ansible behavior in isolation, allowing you to run and test each playbook independently without additional complexity.

To execute any of the **Ansible Playbooks**, you must have **Ansible** installed on your machine. You will also need:

* Access to one or more **Linux hosts**
* Proper **SSH configuration** (key-based authentication is recommended)
* An **inventory file** (or inline host definition) specifying the target machines

You can run a playbook using a command like:

```bash
ansible-playbook -i <inventory> playbooks/<playbook_name>.yml
```

### Important ⚠️

The playbooks in this repository perform changes directly on target Linux systems, such as installing packages, modifying configurations, and managing services. Always review the code before execution and prefer testing in controlled environments (e.g., virtual machines or lab servers) to avoid unintended system changes.

> [!NOTE]  
> Please consider that this is a **study repository**. This means that **no formal GitFlow model** or **structured contribution workflow** will be used. Since the main purpose of the repository is **learning**, **remembering concepts**, and **experimentation**, the organization will follow a **simpler format**. In a **production environment** or in a more serious project where an actual product is being developed, it is **essential** to adopt a **well-defined workflow**, with **specific branches**, a **tagging system**, **version control**, **releases**, and other **best practices**.

