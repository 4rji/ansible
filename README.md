# ansible
"Automate Your Infrastructure: Essential Ansible Scripts for Efficient Execution"




Scripts:

- **ansiconf:** Create hosts for Ansible with aliases and generate the ansible_hosts file.
- **ansicc:** Provides the option to choose a single host or all for Ansible.
- **ansibleplay:** Generates example Ansible playbook files for execution, which need to be modified.
- **ansip:** Alias for pinging all Ansible hosts, using the `-a` parameter for all.
- **ansipp:** Ping a single host and display the Ansible host list.
- **sshansi:** Connects named hosts via SSH at the start of Ansible.
- **ansihost:** Displays hosts and asks if you want to edit them in Ansible.

### First we can ping all the hosts with ansip

```ansip```
![Pasted image 20240416020803](https://github.com/4rji/ansible/assets/118249932/344e8f37-e4e4-49ce-9cf8-e8c8dcef15a2)


### To ping just one host from the list

![[Pasted image 20240416021207.png]]



### With ansihost we can create new hosts:

![[Pasted image 20240416021433.png]]


### Ansicc send bash commands to the hosts or host:

![[Pasted image 20240416021628.png]]

#### or single host: 
![[Pasted image 20240416021731.png]]

### And to connecto to a host via ssh:

![[Pasted image 20240416022008.png]]



### To create playbooks, we can use the templates:
![[Pasted image 20240416023223.png]]
