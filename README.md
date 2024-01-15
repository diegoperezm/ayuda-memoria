
# Table of Contents

1.  [ls](#orgb410405)
    1.  [ls -lrt](#org38843ce)
    2.  [ssh](#orgda8befd)
    3.  [nohup](#orga763022)


<a id="orgb410405"></a>

# ls


<a id="org38843ce"></a>

## ls -lrt

display the contents in the present directory sorted in reverse chronological order. The newest files are shown at the bottom.

    ls -ltr

-l: long listing   
-t: sort by modification time, newest first   
-r: reverses the order of ls command output   

    ls -ltr ../game


<a id="orgda8befd"></a>

## ssh

    ssh-agent bash  
    ssh-add -K ~/.ssh/id_rsa

&#x2014; 

    ssh-add -K ~/.ssh/id_rsa

-K:  Enables GSSAPI-based authentication and forwarding (delegation) of GSSAPI credentials to the server.


<a id="orga763022"></a>

## nohup

nohup: 
run a command immune to hangups, with output to a non-tty

