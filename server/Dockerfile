FROM debian
RUN apt-get update && apt-get install -y nmap
CMD ncat -l 2000 -k -c 'xargs -n1 echo'
