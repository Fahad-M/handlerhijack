# MSF:handler_hijack
MSF:Handler_Hijack is a Tool Designed for Systems Compromised by
Metasploit Multi/Handler and Reverse_tcp payload. 

This tool Connects itself to the Multi/Handler in Metasploit. While the Meterpreter Session
for them Died and then Connected back (to us) The Attacker won't be able to Use the Meterpreter.

Currently I was able to do these to things when Connected. Spam them
that causes lag (tested 90% works) and Send them Message. Sending Message with Ruby did not work
as the Message was not appearing in the MSF Console. So, I tried with Python and it did.
So there are two ways to Connect. Python and Ruby.

Version 1.

## How to Use : 
To use, Start the Multi/Handler Exploit and fully take over a PC with it with Authorization of the Owner. Let the victim use this to defend himself.

## Built for : 
- Kali Linux
- Kali Rolling
- Parrot OS

## Contribute
Submit any Suggestions and Ideas. I want to add this feature of fully taking control over the Attackers PC. Help me do it. 


