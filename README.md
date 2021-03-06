# About
Scripts for setting up convenient utilities and security features on Operating Systems.

# Features
* Security
    * ssh
        * port 60294
        * PermitRootLogin without-password
        * PasswordAuthentication no
* Tools
    * vim, curl, wget, tmux, net-tools, git, zsh, rsync, git, gcc, make, openssl, jdk8.
    * oh-my-zsh: https://github.com/ohmyzsh/ohmyzsh.
    * zsh-autosuggestions: https://github.com/zsh-users/zsh-autosuggestions.
    * Change tmux shorcut from C-b to C-v to resolve conflict with cursor back shortcut of bash/zsh.

# Warning
* __First of all, setup a ssh key__, otherwise you might couldn't login ssh anymore because of security settings. The easiest way is to use __ssh-copy-id__ command
* The ssh port will change to __60294__ for security concern.

# Install
* Ubuntu
```shell script
curl -fsSL "https://github.com/clanceyz/OSEnvScripts/raw/master/linux_ubuntu.sh" | sh
```
