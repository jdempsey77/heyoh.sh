# heyoh.sh
This script can be used to spawn multiple connections to a single port and send expected data.

httpget:  HTTP Request using method of GET to resource of / (Default port 80)<br>
httpput:  HTTP Request using method of PUT to resource of / (Default port 80)<br>
httppost: HTTP Request using method of POST to resource of / (Default port 80)<br>
httpbin:  HTTP Request that contains binary data (Default port 80)<br>
httpxss:  HTTP Request that contains Cross-Site Scriping (XSS) Payload (Default port 80)<br>
wiz:      Connection data of "WIZ" sent to given port (Default port 25)<br>
smtp:     Sends expected SMTP commands (Default port 25)<br>
eicar:    Send the EICAR virus testfile via SMTP (Default port 25)<br>
pop3:	  Retrieves a email message from a POP3 server (Default port 110)<br>
ftp:      Sends expected FTP commands (Default port 21)<br>
ssh:      Sends SSH type banner ie: SSH-1.5-HeyohSSH_2.1 (Default port 22)<br>
boping:   Sends a Back Orifice Ping (Default Port 31337 w/ source port of 53)<br>
<br>
NOTE: for all commands to work properly it is suggested to add an account to remote machine with username and password of heyoh.<br>


Known Issues:

1. OSX version of bash uses their own built-in echo command that doesn't accept "-n" which makes the outut of loopcount not look as pretty on OSX.
