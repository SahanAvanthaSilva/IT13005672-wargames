# IT13005672-wargames #

##Bandit Level 0 → Level 1##
<p>
<pre>
bandit0@melinda:~$ ls
readme
bandit0@melinda:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
</pre>
</p>
-
##Bandit Level 1 → Level 2
<p>
<pre>
 ssh bandit1@bandit.labs.overthewire.org
 bandit1@bandit.labs.overthewire.org's password:boJ9jbbUNNfktd78OOpsqOltutMc3MY1
 
 bandit1@melinda:~$ ls
 bandit1@melinda:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit1@melinda:~$ exit
</pre>
</p>
-
##Bandit Level 2 → Level 3
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit2@bandit.labs.overthewire.org
bandit2@bandit.labs.overthewire.org's password:CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit2@melinda:~$ ls
spaces in this filename
bandit2@melinda:~$ cat spaces\ in\ this\ filename
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit2@melinda:~$ exit
</pre>
</p>
-
##Bandit Level 3 → Level 4
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit3@bandit.labs.overthewire.org
bandit3@bandit.labs.overthewire.org's password:UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit3@melinda:~/inhere$ ls
bandit3@melinda:~/inhere$ ls
bandit3@melinda:~/inhere$ ls -a
.  ..  .hidden
bandit3@melinda:~/inhere$ cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit3@melinda:~/inhere$ exit
</pre>
</p>
-
##Bandit Level 4  → Level 5
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit4@bandit.labs.overthewire.org
bandit4@bandit.labs.overthewire.org's password:pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit4@melinda:~$ ls
inhere
bandit4@melinda:~$ cd inhere
bandit4@melinda:~/inhere$ ls
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
bandit4@melinda:~/inhere$ file ./-file00
./-file00: data
bandit4@melinda:~/inhere$ file ./-file01
./-file01: data
bandit4@melinda:~/inhere$ file ./-file02
./-file02: data
bandit4@melinda:~/inhere$ file ./-file03
./-file03: data
bandit4@melinda:~/inhere$ file ./-file04
./-file04: data
bandit4@melinda:~/inhere$ file ./-file05
./-file05: data
bandit4@melinda:~/inhere$ file ./-file06
./-file06: data
bandit4@melinda:~/inhere$ file ./-file07
./-file07: ASCII text
bandit4@melinda:~/inhere$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit4@melinda:~/inhere$ exit
</pre>
</p>
-
##Bandit Level 5  → Level 6
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit5@bandit.labs.overthewire.org
bandit5@bandit.labs.overthewire.org's password:koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit5@melinda:~$ ls
inhere
bandit5@melinda:~$ cd inhere/
bandit5@melinda:~/inhere$ ls -al
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
                      bandit5@melinda:~/inhere$ exit

</pre>
</p>
-
##Bandit Level 6  → Level 7
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit6@bandit.labs.overthewire.org
bandit6@bandit.labs.overthewire.org's password:DXjZPULLxYr17uwoI01bNLQbtFemEgo7
bandit6@melinda:~$ ls
bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c
find: `/var/lib/cron-apt/_-_etc_-_cron-apt_-_config': Permission denied
find: `/var/lib/mysql': Permission denied
/var/lib/dpkg/info/bandit7.password
find: `/var/cache/ldconfig': Permission denied
find: `/var/log': Permission denied
find: `/var/lock': Permission denied
find: `/var/crash': Permission denied

bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit6@melinda:~$ exit
</pre>
</p>
-
##Bandit Level 7  → Level 8
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit7@bandit.labs.overthewire.org
bandit7@bandit.labs.overthewire.org's password:HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit7@melinda:~$ ls
data.txt
bandit7@melinda:~$ grep millionth data.txt
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit7@melinda:~$ exit
</pre>
</p>
-
##Bandit Level 8  → Level 9
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit8@bandit.labs.overthewire.org
bandit8@bandit.labs.overthewire.org's password:cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit8@melinda:~$ ls
data.txt
bandit8@melinda:~$ sort data.txt | uniq -c
10 TTzMsHH1oVgjm59HjlVTKvGojg3cFYym
10 TYvhnMuLpOdSF4UnMHoAFuJfhm4ub5bd
10 Thw7rjDiq6JPBdYSP5PdpvebvYa4Woio
 1 UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
10 VM88tiT9pkZtuPDK2GGC7IhnqfzHQwkK
10 VZGTL4Yk4dIGQekDBTszeJA545yU01jp
bandit8@melinda:~$ exit
</pre>
</p>
-
##Bandit Level 9  → Level 10
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit9@bandit.labs.overthewire.org
bandit9@bandit.labs.overthewire.org's password:UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

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
bandit9@melinda:~$ exit
</pre>
</p>
-
##Bandit Level  10 → Level 11
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit10@bandit.labs.overthewire.org
bandit10@bandit.labs.overthewire.org's password:truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
bandit10@melinda:~$ ls
data.txt
bandit10@melinda:~$ base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
bandit10@melinda:~$ exit
</pre>
</p>
-
##Bandit Level  11 → Level 12
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit11@bandit.labs.overthewire.org
bandit11@bandit.labs.overthewire.org's password:IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
bandit11@melinda:~$ ls
data.txt
bandit11@melinda:~$ cat data.txt | tr a-zA-Z n-za-mN-ZA-M
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
bandit11@melinda:~$ exit
</pre>
</p>
##Bandit Level  12 → Level 13
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit12@bandit.labs.overthewire.org
bandit12@bandit.labs.overthewire.org's password:5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu


</pre>
</p>







