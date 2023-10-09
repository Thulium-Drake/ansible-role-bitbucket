# Atlassian Bitbucket
This role provides a means to install Atlassian Bitbucket DataCenter on a Linux system.

To start, you need the following:

* A Linux system with Debian 12+ or (RH)EL8+
* A license for Bitbucket DataCenter (or a trial)
* A database for the app to use

It will setup BitBucket in a versioned directory and symlink it to the path from which the
service will run it.

If you don't have access to the Internet, you can change the download URL to a local mirror.

# Usage
* Install the role from Galaxy
* Fill in the variables (see defaults)
* Run Ansible
* ???
* Profit!
