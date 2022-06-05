# simple-tcpserver

to build and run a simple tcp server just use ncat. https://nmap.org/ncat/

for echo server run

  ncat -v -e /bin/cat -k -u -l 11211

to connect it to the bash and have it run as telnet server run

  ncat -v -e /bin/bash -k -u -l 11211
