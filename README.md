##

---------------------------------------------------
- Print Vagarant ssh-config
---------------------------------------------------
    vagrant ssh-config > config

---------------------------------------------------
- Run ansible-playbook using ssh private-key
---------------------------------------------------
    ansible-playbook -i hosts  --private-key /Users/XXXXX/git/vagrant-vm/apache-test/.vagrant/machines/default/virtualbox/private_key install.yaml

---------------------------------------------------
- Export Vagrant box pacakge
---------------------------------------------------
    vagrant package

---------------------------------------------------
- Import Vagrant box pacakge
---------------------------------------------------
    vagrant box add --name mumppache package.box

---------------------------------------------------
- Show Vagrant box list
---------------------------------------------------
    vagrant box list



