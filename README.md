# Travoltaconfused

Travolta confused meme generator [http://travoltaconfused.com/](http://travoltaconfused.com/).

## Installation and development

You need Vagrant and Ansible installed to make installation easier, once you have them:

```bash
cd ansible
ansible-galaxy install -r requirements.txt
cd ..
vagrant up
```

This will install **travoltaconfused** in a virtual machine with ubuntu and
all the dependencies.

You can check It's working going in yout browser to `http://localhost:8080`.

## TODO

We need to make gifs faster.
