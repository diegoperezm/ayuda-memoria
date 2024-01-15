

# ls 

## ls -lrt

 display the contents in the present directory sorted in reverse chronological order. The newest files are shown at the bottom.

```sh
ls -ltr
#+end_src

 -l: long listing \\
 -t: sort by modification time, newest first \\
 -r: reverses the order of ls command output \\

#+begin_src sh  :results output
ls -ltr ../game
```

#+RESULTS:
: total 16
: drwxrwxr-x 2 dapm dapm 4096 dic 21 20:09 shooter
: drwxrwxr-x 3 dapm dapm 4096 dic 21 21:06 c
: drwxrwxr-x 3 dapm dapm 4096 dic 27 20:12 practice
: drwxrwxr-x 5 dapm dapm 4096 dic 29 18:58 ray-lib


## ssh 

```sh
ssh-agent bash  
ssh-add -K ~/.ssh/id_rsa
```

--- 

```sh
ssh-add -K ~/.ssh/id_rsa
```

  -K:  Enables GSSAPI-based authentication and forwarding (delegation) of GSSAPI credentials to the server.

** nohup

nohup: 
run a command immune to hangups, with output to a non-tty
