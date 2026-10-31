*Part 2: K3s and three simple applications*

*** objective ***

*** requirement ***
- 1VM with with the latest stable version of my choice OS.
- K3s in server mode installed.

*** expected specifications ***
- Setup 3 web appli that will run in K3s instance.
- Have access them depending on the HOST used when making a request to the ip `192.168.56.110`.
- Machine name = login followed by 'S'

⚠️
When a client inputs the IP address 192.168.56.110 in their web browser with the HOST app1.com, the server must display app1. When the HOST app2.com is used, the server must display app2. Otherwise, app3 will be selected by default.
⚠️