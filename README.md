Academic-Site
=============

My academic website at www.eecs.berkeley.edu/~maidens/ 

To modify path to give precedence to custom-built curl (that supports sftp):
PATH=/usr/local/bin:$PATH

To upload to web with git-ftp run:
git ftp push -u maidens -p - sftp://login.eecs.berkeley.edu:/home/eecs/maidens