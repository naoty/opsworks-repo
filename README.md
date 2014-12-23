# opsworks-repo

Chef repository including opsworks-cookbooks

## Usage

```bash
$ bundle install
$ vagrant box add opscode-ubuntu-12.04 http://opscode-vm-bento.s3.amazonaws.com/vagrant/virtualbox/opscode_ubuntu-12.04_chef-provisionerless.box
$ vagrant up
$ vagrant ssh-config --host vagrant-ubuntu >> ~/.ssh/config
$ bin/knife solo bootstrap vagrant-ubuntu
```
