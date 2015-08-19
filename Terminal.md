####bandit - Terminal

```
---
> BS8bqB1kqkinKJjuxL6k072Qq9NRwQpR
bandit17@melinda:~$ exit
logout
Connection to localhost closed.
bandit16@melinda:/tmp/vv$ exit
logout
There are stopped jobs.
bandit16@melinda:/tmp/vv$ exit
logout
Connection to bandit.labs.overthewire.org closed.
[root@localhost Desktop]# ssh bandit18@bandit.labs.overthewire.org

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit18@bandit.labs.overthewire.org's password: 
               
      ,----..            ,----,          .---. 
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' ' 
  |   :  | ; | ' ;    |.';  ; ;   \  \;      : 
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ; 
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"  
     \   \ .'        ;   |.'       \   \ ;     
  www. `---` ver     '---' he       '---" ire.org     
               
              
Welcome to the OverTheWire games machine!

If you find any problems, please report them to Steven on
irc.overthewire.org.

--[ Playing the games ]--

  This machine holds several wargames. 
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ and /proc/ is disabled
  so that users can not snoop on eachother.

  Please play nice:
      
    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

      -m32                    compile for 32bit
      -fno-stack-protector    disable ProPolice
      -Wl,-z,norelro          disable relro 

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levels by a local
  firewall.

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For questions or comments, contact us through IRC on
  irc.overthewire.org.


Byebye !
Connection to bandit.labs.overthewire.org closed.
[root@localhost Desktop]# ssh bandit18@bandit.labs.overthewire.org cat readme

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit18@bandit.labs.overthewire.org's password: 
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
[root@localhost Desktop]# ^C
[root@localhost Desktop]# ssh bandit19@bandit.labs.overthewire.org cat readme

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit19@bandit.labs.overthewire.org's password: 

[root@localhost Desktop]# bandit18@bandit.labs.overthewire.org's password: 
> IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
> 
> ^C
[root@localhost Desktop]# ssh bandit19@bandit.labs.overthewire.org cat readme

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit19@bandit.labs.overthewire.org's password: 
cat: readme: No such file or directory
[root@localhost Desktop]# ssh bandit19@bandit.labs.overthewire.org

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit19@bandit.labs.overthewire.org's password: 
               
      ,----..            ,----,          .---. 
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' ' 
  |   :  | ; | ' ;    |.';  ; ;   \  \;      : 
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ; 
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"  
     \   \ .'        ;   |.'       \   \ ;     
  www. `---` ver     '---' he       '---" ire.org     
               
              
Welcome to the OverTheWire games machine!

If you find any problems, please report them to Steven on
irc.overthewire.org.

--[ Playing the games ]--

  This machine holds several wargames. 
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ and /proc/ is disabled
  so that users can not snoop on eachother.

  Please play nice:
      
    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

      -m32                    compile for 32bit
      -fno-stack-protector    disable ProPolice
      -Wl,-z,norelro          disable relro 

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levels by a local
  firewall.

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For questions or comments, contact us through IRC on
  irc.overthewire.org.


bandit19@melinda:~$ clear

bandit19@melinda:~$ ls
bandit20-do
bandit19@melinda:~$ ./bandit20-do
Run a command as another user.
  Example: ./bandit20-do id
bandit19@melinda:~$ ./bandinr20-do id
-bash: ./bandinr20-do: No such file or directory
bandit19@melinda:~$ ./bandint20-do id
-bash: ./bandint20-do: No such file or directory
bandit19@melinda:~$ ./bandit20-do id
uid=11019(bandit19) gid=11019(bandit19) euid=11020(bandit20) groups=11020(bandit20),11019(bandit19)
bandit19@melinda:~$ ./bandit20-do whoami
bandit20
bandit19@melinda:~$ ./bandit20-do cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
bandit19@melinda:~$ exi
-bash: exi: command not found
bandit19@melinda:~$ exit
logout
Connection to bandit.labs.overthewire.org closed.
[root@localhost Desktop]# ssh bandit20@bandit.labs.overthewire.org

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit20@bandit.labs.overthewire.org's password: 
               
      ,----..            ,----,          .---. 
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' ' 
  |   :  | ; | ' ;    |.';  ; ;   \  \;      : 
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ; 
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"  
     \   \ .'        ;   |.'       \   \ ;     
  www. `---` ver     '---' he       '---" ire.org     
               
              
Welcome to the OverTheWire games machine!

If you find any problems, please report them to Steven on
irc.overthewire.org.

--[ Playing the games ]--

  This machine holds several wargames. 
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ and /proc/ is disabled
  so that users can not snoop on eachother.

  Please play nice:
      
    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

      -m32                    compile for 32bit
      -fno-stack-protector    disable ProPolice
      -Wl,-z,norelro          disable relro 

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levels by a local
  firewall.

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For questions or comments, contact us through IRC on
  irc.overthewire.org.


bandit20@melinda:~$ clear

bandit20@melinda:~$ ls
suconnect
bandit20@melinda:~$ ./suconnect 
Usage: ./suconnect <portnumber>
This program will connect to the given port on localhost using TCP. If it receives the correct password from the other side, the next password is transmitted back.
bandit20@melinda:~$ Write failed: Broken pipe
[root@localhost Desktop]# ssh bandit20@bandit.labs.overthewire.org

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit20@bandit.labs.overthewire.org's password: 
               
      ,----..            ,----,          .---. 
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' ' 
  |   :  | ; | ' ;    |.';  ; ;   \  \;      : 
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ; 
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"  
     \   \ .'        ;   |.'       \   \ ;     
  www. `---` ver     '---' he       '---" ire.org     
               
              
Welcome to the OverTheWire games machine!

If you find any problems, please report them to Steven on
irc.overthewire.org.

--[ Playing the games ]--

  This machine holds several wargames. 
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ and /proc/ is disabled
  so that users can not snoop on eachother.

  Please play nice:
      
    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

      -m32                    compile for 32bit
      -fno-stack-protector    disable ProPolice
      -Wl,-z,norelro          disable relro 

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levels by a local
  firewall.

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For questions or comments, contact us through IRC on
  irc.overthewire.org.


bandit20@melinda:~$ clear

bandit20@melinda:~$ ls
suconnect
bandit20@melinda:~$ ./suconnect 
Usage: ./suconnect <portnumber>
This program will connect to the given port on localhost using TCP. If it receives the correct password from the other side, the next password is transmitted back.
bandit20@melinda:~$ nc -1 3222
nc: invalid option -- '1'
This is nc from the netcat-openbsd package. An alternative nc is available
in the netcat-traditional package.
usage: nc [-46bCDdhjklnrStUuvZz] [-I length] [-i interval] [-O length]
	  [-P proxy_username] [-p source_port] [-q seconds] [-s source]
	  [-T toskeyword] [-V rtable] [-w timeout] [-X proxy_protocol]
	  [-x proxy_address[:port]] [destination] [port]
bandit20@melinda:~$ nc -1 3222 < /etc/bandit_pass/bandit20
nc: invalid option -- '1'
This is nc from the netcat-openbsd package. An alternative nc is available
in the netcat-traditional package.
usage: nc [-46bCDdhjklnrStUuvZz] [-I length] [-i interval] [-O length]
	  [-P proxy_username] [-p source_port] [-q seconds] [-s source]
	  [-T toskeyword] [-V rtable] [-w timeout] [-X proxy_protocol]
	  [-x proxy_address[:port]] [destination] [port]
bandit20@melinda:~$ nc -l 3222 < /etc/bandit_pass/bandit20
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
bandit20@melinda:~$ GbKksEFF4yrVs6il55v6gwY5aVje5f0j
-bash: GbKksEFF4yrVs6il55v6gwY5aVje5f0j: command not found
bandit20@melinda:~$ nc
This is nc from the netcat-openbsd package. An alternative nc is available
in the netcat-traditional package.
usage: nc [-46bCDdhjklnrStUuvZz] [-I length] [-i interval] [-O length]
	  [-P proxy_username] [-p source_port] [-q seconds] [-s source]
	  [-T toskeyword] [-V rtable] [-w timeout] [-X proxy_protocol]
	  [-x proxy_address[:port]] [destination] [port]
bandit20@melinda:~$ nc -l 3222
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
bandit20@melinda:~$ exit
logout
Connection to bandit.labs.overthewire.org closed.
[root@localhost Desktop]# ssh bandit21@bandit.labs.overthewire.org

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit21@bandit.labs.overthewire.org's password: 
               
      ,----..            ,----,          .---. 
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' ' 
  |   :  | ; | ' ;    |.';  ; ;   \  \;      : 
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ; 
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"  
     \   \ .'        ;   |.'       \   \ ;     
  www. `---` ver     '---' he       '---" ire.org     
               
              
Welcome to the OverTheWire games machine!

If you find any problems, please report them to Steven on
irc.overthewire.org.

--[ Playing the games ]--

  This machine holds several wargames. 
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ and /proc/ is disabled
  so that users can not snoop on eachother.

  Please play nice:
      
    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

      -m32                    compile for 32bit
      -fno-stack-protector    disable ProPolice
      -Wl,-z,norelro          disable relro 

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levels by a local
  firewall.

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For questions or comments, contact us through IRC on
  irc.overthewire.org.


bandit21@melinda:~$ 
```
