# hello
Project's description
made some changes
add one line on master branch

dnt@dnt-OptiPlex-7010:~/DNT$ git clone https://forge-sysnet.rmm.sagem/git/esm-ctrl-git-v3
Cloning into 'esm-ctrl-git-v3'...
Username for 'https://forge-sysnet.rmm.sagem': g562044
Password for 'https://g562044@forge-sysnet.rmm.sagem': 
remote: Counting objects: 64175, done.
remote: Compressing objects: 100% (40876/40876), done.
error: RPC failed; curl 56 GnuTLS recv error (-9): A TLS packet with unexpected length was received.
fatal: The remote end hung up unexpectedly
fatal: early EOF
fatal: index-pack failed

dnt@dnt-OptiPlex-7010:~/DNT$ git clone https://forge-sysnet.rmm.sagem/git/esm-ctrl-git-v3
Cloning into 'esm-ctrl-git-v3'...
Username for 'https://forge-sysnet.rmm.sagem': g562044
Password for 'https://g562044@forge-sysnet.rmm.sagem': 
remote: Counting objects: 64175, done.
remote: Compressing objects: 100% (40876/40876), done.
eceiving objects:  22% (15118/64175), 32.95MiB | 72.00 KiB/s

dnt@dnt-OptiPlex-7010:~/DNT$ git config -l
http.postbuffer=1048576000
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
user.name=will
user.email=will.li@sagemcom.com
http.sslverify=false

dnt@dnt-OptiPlex-7010:~/DNT$ echo $GIT_SSL_NO_VERIFY 
1

dnt@dnt-OptiPlex-7010:~/DNT$ git --version
git version 2.17.1

g562044@shz-p0000601fl:~/DNT$ git clone https://forge-sysnet.rmm.sagem/git/esm-ctrl-git-v3
Cloning into 'esm-ctrl-git-v3'...
Username for 'https://forge-sysnet.rmm.sagem': g562044
Password for 'https://g562044@forge-sysnet.rmm.sagem': 
remote: Counting objects: 64175, done.
remote: Compressing objects: 100% (40876/40876), done.
error: RPC failed; curl 56 GnuTLS recv error (-9): A TLS packet with unexpected length was received.
fatal: The remote end hung up unexpectedly
fatal: early EOF
fatal: index-pack failed
g562044@shz-p0000601fl:~/DNT$ 

