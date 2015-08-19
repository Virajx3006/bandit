###bandit war games - Viraj Jayasekara

######Level0:
* [root@localhost Desktop]# ssh bandit0@bandit.labs.overthewire.org

######Level0->Level1:
* bandit0@melinda:~$ ls
* readme
* bandit0@melinda:~$ cat readme
* boJ9jbbUNNfktd78OOpsqOltutMc3MY1

######Level1->Level2:
* bandit1@melinda:~$ ls
* -
* bandit1@melinda:~$ cat ./-
* V1DtqXWVFXTvM2F0k09SHz0YwRINYA9

######Level2->Level3:
* bandit2@melinda:~$ ls
* spaces in this filename
* bandit2@melinda:~$ cat "spaces in this filename"
* UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

######Level3->Level4:
* bandit3@melinda:~$ ls
* inhere
* bandit3@melinda:~$ cd inhere
* bandit3@melinda:~/inhere$ ls -la
* total 12
* drwxr-xr-x 2 root    root    4096 Nov 14  2014 .
* drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..
* -rw-r----- 1 bandit4 bandit3   33 Nov 14  2014 .hidden
* bandit3@melinda:~/inhere$ cat .hidden
* pIwrPrtPN36QITSp3EQaw936yaFoFgAB

######Level4->Level5:


