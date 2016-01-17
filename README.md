# Travoltaconfused

Travolta confused meme generator [http://travoltaconfused.com/](http://travoltaconfused.com/).

## Installation and development

You need [Vagrant](https://www.vagrantup.com/) and [Ansible](http://www.ansible.com/)
installed to automatize the creation of the development environment.

Inside the project you can install It with these commands:

```bash
cd ansible
ansible-galaxy install -r requirements.txt
cd ..
vagrant up
```

This will install **travoltaconfused** in a virtual machine with ubuntu and
all the dependencies.

You can check It's working going in your browser to `http://localhost:8080`.

## TODO

We need to make gifs faster.
