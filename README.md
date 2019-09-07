# vulnserver_stack_based-buffer_overflow
this repository gives you details commands about Stack based buffer overflow


1. open the file fuzz.py and send buffer as per your conviniance

2. create a pattern to get the address of EIP -- use pattern_create  from metasploit 

get the value and then run pattern_offset from metasploit  -- get the exect offset 

run the create pattern script 

3.  add extra 4 bytes and control the eip 

4. create badchars -- https://bulbsecurity.com/finding-bad-characters-with-immunity-debugger-and-mona-py/

find out bad chars !! remove them 

5 now create shelcode with  - msfvenom --with your removed bad chars

6. get a reverse shell 


to  get a detailed idea  about bufferoverflow  visit -- https://blog.certcube.com/oscp-detail-guide-to-stack-buffer-overflow-1/

follow all 9 blogs you will get a decent knowledge about bof which will help you crack the OSCP Bof
