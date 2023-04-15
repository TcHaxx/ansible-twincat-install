# ansible-twincat-install
Install `TwinCAT 3.1` with all features on a remote Windows machine with Ansible

> **NOTE**
> The TwinCAT installer *needs* UI (interactive mode), despite having silent option enabled.  
> Thus, this playbook uses `win_psexec`, all other methods failed.  
> This was the only way to get TwinCAT installed properly.  

See also [Beckhoff Infosys](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_installation/5318976651.html).

## Resource
* [gist: densogiaichned/InstallTcAnsible.yml](https://gist.github.com/densogiaichned/491668e14bb3dd34a1ff363ea840334e)