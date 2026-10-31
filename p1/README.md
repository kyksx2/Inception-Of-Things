*Part 1: K3s and Vagrant*

*** objective ***
write a Vagrantfile using the latest stable version of my choice OS.

*** requirement ***
- It is advised to allow only the bare minimum in terms of resources (1CPU and 512 or 1024 MB of RAM).
- The machine must be run using Vagrant

*** expected specifications ***
- Machine names = login of sommeone of the team.
- Hostname of the first machine --> followed by 'S' (like server).
- Hostname of the second machine --> followed by 'SW' (like server worker).
- IP of the first machine = `192.168.56.110`
- IP of the second machine = `192.168.56.111`
- SSH connection passwordless for both machines.
- Server have K3s in "controller mode".
- Serverworker in "agent mode".
⚠️ use kubectl ⚠️