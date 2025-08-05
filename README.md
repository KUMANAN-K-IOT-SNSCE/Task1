# Task1
Use Nmap to scan the open ports of the local host
Use -sS for stealth scan, -p- to scan all ports
Use -oA target to store the output in the name target
Use .xml to the output in xml format
then save the output in html format
 sudo nmap -sS -Pn 157.49.98.83 -p- -oA target
 cat target.xml
 xsltproc target.xml -o target.html
