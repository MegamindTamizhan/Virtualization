# Vagrant Commands You Need to Know

* **vagrant up:** Bring a box online.
* **vagrant status:** Show current box status.
* **vagrant suspend:** Pause the current box.
* **vagrant resume:** Resume the current box.
* **vagrant halt:** Shutdown the current box.
* **vagrant destroy:** Destroy the current box. By running this command, you will lose any data stored on the box.
* **vagrant snapshot:** Take a snapshot of the current box.


### Vagrant Installation in Ubuntu

```
$ sudo apt update && sudo apt install vagrant
```

Check the version:

```
$ vagrant --version
```

### Install a Box 

```
$ vagrant init [box name [url]]
```

Eg.,

```
$ vagrant init ubuntu/xenial64
```

**Output:** **Vagrantfile** will placed in the current directory. You are now ready to "vagrant up" your first Virtual environment.

Before "vagrant up" configure the Virtualbox settings in **Vagrantfile** and then Up

```
$ vagrant up
```

For the first it will download the box.

```
$ vagrant ssh
```

This command will do ssh to the VM that you created


### List boxes

```
$ vagrant box list
```
### Show status of ALL boxes

```
vagrant global-status
```

```
vagrant halt
```

### Remove stale boxes from cache, then Show status of ALL remaining boxes

```
vagrant global-status --prune
```







  

