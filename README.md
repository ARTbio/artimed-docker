Build docker images for [galaxy](https://github.com/galaxyproject/galaxy) using ansible playbooks.
----
Clone this repo and its submodules, then (assuming you would like to build locally):  
```
ansible-playbook -i "localhost," -c local build_images.yml
```

You can change settings in inventory.yml and use a different playbook by exchanging ansible-artimed
with your favorite playbook in build_images.yml.
