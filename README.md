# Knifenet
<p>is a computer networking utility for reading from and writing to network connections using TCP or UDP. </p>
<br />
<p>Its list of features includes port scanning, transferring files, and port listening, and it can be used as a backdoor.</p>
# Usage : 
<p>knifenet Net Tool
<br />
Usage: knifenet.py -t target_host -p port
<br />
-l --listen 		- listen on [host]:[port] for incoming connections
<br />
-e --execute=file_to_run - execute the given file upon receiving a connection
<br />
-c --command 	- initialize a command shell
<br />
-u --upload=destination - upon receiving connection upload a	file and write to [destination]
<br />
<br />
Examples: 
<br />
knifenet.py -t 192.168.0.1 -p 5555 -l -c
<br />
knifenet.py -t 192.168.0.1 -p 5555 -l -u=c:\target.exe
<br />
knifenet.py -t 192.168.0.1 -p 5555 -l -e="cat /etc/passwd"
<br />
echo 'ABCDEFGHI' | ./knifenet.py -t 192.168.11.12 -p 135
<br />
<br />
</p>
<h4> Enjoy ;) </h4>

