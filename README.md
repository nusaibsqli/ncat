# ncat
This Netcat Backdoor to control victims Pc

Create by ghosthub (b@b@y)

usage: nCat.py [-h] [-s] [-u UPLOAD UPLOAD] {c,s} target

Python netcat. Drop files, download files, execute, and sniff.

positional arguments:
  {c,s}                 Pick if you serve or are the client
  target                IP and port you want to target (IP:port)

optional arguments:
  -h, --help            show this help message and exit
  -s, --shell           Open a shell
  -u UPLOAD UPLOAD, --upload UPLOAD UPLOAD
                        On receive, put the file located locally at argv[0] in
                        the specified destination argv[1] on the server
