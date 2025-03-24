# UnderPass (HTB) CTF write-up

## Objective

This is a write-up for UnderPass, an easy level difficulty vulnerable machine on HackTheBox.
Note that at the time of this publication the machine is still active, so big spoilers and hints are to be used with caution.

### Skills Learned

- UDP port scanning
- What is daloRadius and how does it work.
- MD5 hash cracking
- Mosh service, operation, and privilege escalation.

### Tools Used

- Kali Linux, and through it:
  - nmap
  - snmpwalk
  - hashcat
  - ssh
  - scp
  - manual PE enumeration
  - LinPEAS
  - mosh service
- daloRADIUS
  
## Steps

1. Network scanning and open ports enumeration:

![4-nmap](https://github.com/user-attachments/assets/ded41b32-8a62-4295-81d0-eaf814b75682)
![3-nmap-udp](https://github.com/user-attachments/assets/2d624ae8-ba69-4a8d-9c82-9f3e7940637d)

2. daloRADIUS login:

![7-login-succ](https://github.com/user-attachments/assets/851d2034-39fb-4a08-a8db-3b4ab7ee6445)

3. Users list:

![9-users-list](https://github.com/user-attachments/assets/04177023-8c80-418a-b040-5eecc7946088)

4. MD5 hash cracking:

![10-hashcat](https://github.com/user-attachments/assets/146c4fe1-36f0-40a3-975f-dcafd211956c)

..to access the rest of the steps, please download the attached file (since this post will become too large).



