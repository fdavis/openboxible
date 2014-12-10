Welcome to my openboxible (openstack virtualbox ansible) repo
---

Ideally you have a 14.04 LTS with your user and password, you can change the remote user in `roles/init/tasks/main.yml` and after creating a controller/network/compute nodes just like in a tutorial I started with you'll be ready to go.... ? (this all suddenly seems esoteric and unhelpful to make public)


I hope this three node setup will be as easy as:
```bash
ansible-playbook -k -K init.yml
ansible-playbook site.yml
```
