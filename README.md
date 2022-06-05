# simple-tcpserver

to build and run a simple tcp server just use ncat. https://nmap.org/ncat/

for echo server run

	ncat -v -e /bin/cat -k -l 11211

to connect it to the bash and have it run as telnet server run

	ncat -v -e /bin/bash -k -l 11212

if you do not want to install ncat use the dockerized versions in docker hub https://hub.docker.com/

	
