###bandit war games - Viraj Jayasekara

######Level0:
```
[root@localhost Desktop]# ssh bandit0@bandit.labs.overthewire.org
```

######Level0->Level1:
```
bandit0@melinda:~$ ls
readme
bandit0@melinda:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```

######Level1->Level2:
```
bandit1@melinda:~$ ls
-
bandit1@melinda:~$ cat ./-
V1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```

######Level2->Level3:
```
bandit2@melinda:~$ ls
spaces in this filename
bandit2@melinda:~$ cat "spaces in this filename"
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```

######Level3->Level4:
```
bandit3@melinda:~$ ls
inhere
bandit3@melinda:~$ cd inhere
bandit3@melinda:~/inhere$ ls -la
total 12
drwxr-xr-x 2 root    root    4096 Nov 14  2014 .
drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..
-rw-r----- 1 bandit4 bandit3   33 Nov 14  2014 .hidden
bandit3@melinda:~/inhere$ cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```

######Level4->Level5:
```
bandit4@melinda:~$ ls
inhere
bandit4@melinda:~$ cd inhere
bandit4@melinda:~/inhere$ ls -la
total 48
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file00
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file01
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file02
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file03
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file04
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file05
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file06
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file07
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file08
-rw-r----- 1 bandit5 bandit4   33 Nov 14  2014 -file09
drwxr-xr-x 2 root    root    4096 Nov 14  2014 .
drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..
bandit4@melinda:~/inhere$ file ./-*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@melinda:~/inhere$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```

######Level5->Level6:
```
bandit5@melinda:~$ ls 
inhere
bandit5@melinda:~$ cd inhere
bandit5@melinda:~/inhere$ ls -la
total 88
drwxr-x--- 22 root bandit5 4096 Nov 14  2014 .
drwxr-xr-x  3 root root    4096 Nov 14  2014 ..
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere00
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere01
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere02
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere03
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere04
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere05
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere06
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere07
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere08
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere09
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere10
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere11
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere12
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere13
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere14
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere15
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere16
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere17
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere18
drwxr-x---  2 root bandit5 4096 Nov 14  2014 maybehere19
bandit5@melinda:~/inhere$ find ./ -size 1033c
./maybehere07/.file2
bandit5@melinda:~/inhere$ cat ./maybehere07/.file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

######Level6->Level7:
```
bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

######Level7->Level8:
```
bandit7@melinda:~$ ls
data.txt
bandit7@melinda:~$ cat data.txt | grep millionth
millionth	cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```

######Level8->Level9:
```
bandit8@melinda:~$ ls
data.txt
bandit8@melinda:~$ cat data.txt | sort | uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```

######Level9->Level10:
```
bandit9@melinda:~$ ls
data.txt
bandit9@melinda:~$ strings data.txt | grep '='
epr~F=K
7?YD=
?M=HqAH
/(Ne=
C=_"
I========== the6
z5Y=
`h(8=`
n\H=;
========== password
========== ism
N$=&
l/a=L)
f=C(
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
ie)=5e
```

######Level10->Level11:
```
bandit10@melinda:~$ ls
data.txt
bandit10@melinda:~$ base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```

######Level11->Level12:
```
bandit11@melinda:~$ ls
data.txt
bandit11@melinda:~$ cat data.txt | tr a-zA-Z n-za-mN-ZA-M
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```

######Level12->Level13:
```
bandit12@melinda:~$ ls
data.txt
bandit12@melinda:~$ file data.txt
data.txt: ASCII text
bandit12@melinda:~$ mkdir /tmp/vvv
bandit12@melinda:~$ cd /tmp/vvv
bandit12@melinda:/tmp/vvv$ xxd -r ~/data.txt > data.txt
bandit12@melinda:/tmp/vvv$ file data.txt
data.txt: gzip compressed data, was "data2.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/vvv$ zcat data.txt > dataNew
bandit12@melinda:/tmp/vvv$ ls
data.txt  dataNew
bandit12@melinda:/tmp/vvv$ file dataNew
dataNew: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/vvv$ bzip2 -d dataNew
bzip2: Can't guess original name for dataNew -- using dataNew.out
bandit12@melinda:/tmp/vvv$ ls
data.txt  dataNew.out
bandit12@melinda:/tmp/vvv$ file dataNew.out
dataNew.out: gzip compressed data, was "data4.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/vvv$ zcat dataNew.out > evenNewer
bandit12@melinda:/tmp/vvv$ ls
data.txt  dataNew.out  evenNewer
bandit12@melinda:/tmp/vvv$ file evenNewer
evenNewer: POSIX tar archive (GNU)
bandit12@melinda:/tmp/vvv$ tar -xvf evenNewer
data5.bin
bandit12@melinda:/tmp/vvv$ file data5.bin
data5.bin: POSIX tar archive (GNU)
bandit12@melinda:/tmp/vvv$ tar -xvf data5.bin
data6.bin
bandit12@melinda:/tmp/vvv$ file data6.bin
data6.bin: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/vvv$ bzip2 -d data6.bin
bzip2: Can't guess original name for data6.bin -- using data6.bin.out
bandit12@melinda:/tmp/vvv$ ls
data.txt  data5.bin  data6.bin.out  dataNew.out  evenNewer
bandit12@melinda:/tmp/vvv$ file data6.bin.out
data6.bin.out: POSIX tar archive (GNU)
bandit12@melinda:/tmp/vvv$ tar -xvf data6.bin.out
data8.bin
bandit12@melinda:/tmp/vvv$ file data8.bin
data8.bin: gzip compressed data, was "data9.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/vvv$ zcat data8.bin > lost
bandit12@melinda:/tmp/vvv$ ls
data.txt  data5.bin  data6.bin.out  data8.bin  dataNew.out  evenNewer  lost
bandit12@melinda:/tmp/vvv$ file lost
lost: ASCII text
bandit12@melinda:/tmp/vvv$ cat lost
The password is 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```

######Level13->Level14:
```
bandit13@melinda:~$ ls
sshkey.private
bandit13@melinda:~$ ssh -i sshkey.private bandit14@localhost
Could not create directory '/home/bandit13/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.
Are you sure you want to continue connecting (yes/no)? yes
Failed to add the host to the list of known hosts (/home/bandit13/.ssh/known_hosts).

bandit14@melinda:~$ cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```

######Level14->Level15:
```



