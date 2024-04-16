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

![Pasted image 20240416021207](https://github.com/4rji/ansible/assets/118249932/cc313ac6-4e45-4d39-80cc-27bd168e7382)



### With ansihost we can create new hosts:

![Pasted image 20240416021433](https://github.com/4rji/ansible/assets/118249932/e9604ce6-b40d-4e47-86ed-ed0900086d35)


### Ansicc send bash commands to the hosts or host:

![Pasted image 20240416021628](https://github.com/4rji/ansible/assets/118249932/55b7b72b-b1a2-49b3-ae51-e7d3053600e4)

#### or single host: 
![Pasted image 20240416021731](https://github.com/4rji/ansible/assets/118249932/55ed07f2-7d4f-4144-8640-7c7801858a93)

### And to connecto to a host via ssh:

![Pasted image 20240416022008](https://github.com/4rji/ansible/assets/118249932/92f68e42-78a5-4cc6-b9c4-258ba1a9b62f)



### To create playbooks, we can use the templates:
![Pasted image 20240416023223](https://github.com/4rji/ansible/assets/118249932/3858a1a6-f96e-4774-9219-5018169f215f)
