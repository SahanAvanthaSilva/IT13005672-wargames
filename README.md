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
bandit12@melinda:~$ ls
data.txt
bandit12@melinda:~$ mkdir /tmp/sahan321
bandit12@melinda:~$ cd /tmp/sahan321
bandit12@melinda:/tmp/sahan321$ xxd -r ~/data.txt >data
bandit12@melinda:/tmp/sahan321$ ls
data
bandit12@melinda:/tmp/sahan321$ file data
data: gzip compressed data, was "data2.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/sahan321$ gunzip data
gzip: data: unknown suffix -- ignored

bandit12@melinda:/tmp/sahan321$ zcat data > data.txt
bandit12@melinda:/tmp/sahan321$ ls
data  data.gz  data.txt  datadata
bandit12@melinda:/tmp/sahan321$ file data.txt
data.txt: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/sahan321$ bzip2 -d data.txt
bzip2: Can't guess original name for data.txt -- using data.txt.out
bandit12@melinda:/tmp/sahan321$ ls
data  data.gz  data.txt.out  datadata
andit12@melinda:/tmp/sahan321$ file data.txt.out
data.txt.out: gzip compressed data, was "data4.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/sahan321$ zcat data.txt.out > newdata
bandit12@melinda:/tmp/sahan321$ ls
data  data.gz  data.txt.out  datadata  newdata
bandit12@melinda:/tmp/sahan321$ file newdata
newdata: POSIX tar archive (GNU)
bandit12@melinda:/tmp/sahan321$ ls
data  data.gz  data.txt.out  datadata  newdata
bandit12@melinda:/tmp/sahan321$ tar -xvf newdata
data5.bin
bandit12@melinda:/tmp/sahan321$ file data5.bin
data5.bin: POSIX tar archive (GNU)
bandit12@melinda:/tmp/sahan321$ tar -xvf data5.bin
data6.bin
bandit12@melinda:/tmp/sahan321$ file data6.bin
data6.bin: bzip2 compressed data, block size = 900k
bandit12@melinda:/tmp/sahan321$ bzip2 -d data6.bin
bzip2: Can't guess original name for data6.bin -- using data6.bin.out

bandit12@melinda:/tmp/sahan321$ file data6.bin.out
data6.bin.out: POSIX tar archive (GNU)
bandit12@melinda:/tmp/sahan321$ tar -xvf data6.bin.out
data8.bin
bandit12@melinda:/tmp/sahan321$ file data8.bin
data8.bin: gzip compressed data, was "data9.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression
bandit12@melinda:/tmp/sahan321$ zcat data8.bin > pw
bandit12@melinda:/tmp/sahan321$ file pw
pw: ASCII text
bandit12@melinda:/tmp/sahan321$ cat pw
The password is 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
bandit12@melinda:/tmp/sahan321$ exit

</pre>
</p>
-
##Bandit Level  13 → Level 14
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit13@bandit.labs.overthewire.org
bandit13@bandit.labs.overthewire.org's password:8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
bandit13@melinda:~$ ls
sshkey.private
bandit13@melinda:~$ ssh -i sshkey.private bandit14@localhost
Could not create directory '/home/bandit13/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.
Are you sure you want to continue connecting (yes/no)? yes


 cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
bandit14@melinda:~$ exit

</pre>
</p>
-
##Bandit Level  14 → Level 15
<p>
<pre>
Sahan.Sahan-PC] ➤ ssh bandit14@bandit.labs.overthewire.org
bandit14@bandit.labs.overthewire.org's password:4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
bandit14@melinda:~$ telnet localhost 30000
Trying 127.0.0.1...
Connected to localhost.
Escape character is '^]'.
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
Correct!
BfMYroe26WYalil77FoDi9qh59eK5xNr

Connection closed by foreign host.
bandit14@melinda:~$ exit
</pre>
</p>
-
##Bandit Level  15 → Level 16
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit15@bandit.labs.overthewire.org
bandit15@bandit.labs.overthewire.org's password:BfMYroe26WYalil77FoDi9qh59eK5xNr

bandit15@melinda:~$ openssl s_client -connect localhost:30001 -quiet
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
BfMYroe26WYalil77FoDi9qh59eK5xNr
Correct!
cluFn7wTiGryunymYOu4RcffSxQluehd

read:errno=0
bandit15@melinda:~$ exit

</pre>
</p>
-
##Bandit Level  16 → Level 17
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit16@bandit.labs.overthewire.org
bandit16@bandit.labs.overthewire.org's password:cluFn7wTiGryunymYOu4RcffSxQluehd
bandit16@melinda:~$ nmap -p 31000-32000 localhost

Starting Nmap 6.40 ( http://nmap.org ) at 2015-08-19 19:17 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.00085s latency).
Not shown: 996 closed ports
PORT      STATE SERVICE
31046/tcp open  unknown
31518/tcp open  unknown
31691/tcp open  unknown
31790/tcp open  unknown
31960/tcp open  unknown

Nmap done: 1 IP address (1 host up) scanned in 0.08 seconds
bandit16@melinda:~$ openssl s_client -connect localhost:31046
CONNECTED(00000003)
140737354045088:error:140770FC:SSL routines:SSL23_GET_SERVER_HELLO:unknown protocol:s23_clnt.c:795:
---
no peer certificate available
---
No client certificate CA names sent
---
SSL handshake has read 7 bytes and written 295 bytes
---
New, (NONE), Cipher is (NONE)
Secure Renegotiation IS NOT supported
Compression: NONE
Expansion: NONE
---
bandit16@melinda:~$ openssl s_client -connect localhost:31518
CONNECTED(00000003)
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
---
Certificate chain
 0 s:/CN=li190-250.members.linode.com
   i:/CN=li190-250.members.linode.com
---
Server certificate
-----BEGIN CERTIFICATE-----
MIIC3jCCAcagAwIBAgIJAI5QiWZw4YHbMA0GCSqGSIb3DQEBCwUAMCcxJTAjBgNV
BAMTHGxpMTkwLTI1MC5tZW1iZXJzLmxpbm9kZS5jb20wHhcNMTQxMTE0MTAyODA0
WhcNMjQxMTExMTAyODA0WjAnMSUwIwYDVQQDExxsaTE5MC0yNTAubWVtYmVycy5s
aW5vZGUuY29tMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAsKmy9o5z
WU+1EH7Z3bB5TGQA+16zXDcEJy6tZWZ8CDrRyQXiahendp45BWUc/ZuLDo0+B3Wt
ZXjofmLw/F4fmR+8X1s1fQZX2dFt920qEm7LxqzWd0c7FdHiBwwRrwhkk+3cQpOB
TTGdLWEgpdmwwNZDTUdsDLzjDczPnju6T6p6ArTECztPbmTjfY4QIRtC6capL1Z+
yPJSQVAuAMEX1wTDWTGdm0VV7oW4F5cGZutf6QAP51jdhSyZuGilIPHbnj0l6Qc7
a7+OtEsEGi31aJ8KpRf7LNZ7DXCuoB3Hf75Pd6VjDgoOIagcH0NYqa75gEjBkGzs
ktLWykT7ag7fKwIDAQABow0wCzAJBgNVHRMEAjAAMA0GCSqGSIb3DQEBCwUAA4IB
AQCaZdUNAj8WDEKWdoU3LNXUBJlTJwiWBrh550PbHSQORcCz2K0kiMei1A4ojK2N
dMHFGAqAeUEaxtz92p2BoFpZasAtdSa3u63tBckFhfUolIS1TC7Cj51y19ysTeep
fGPFpuPCVqVPsruei8Z/iqn3bFIhQQdmumeePZQdPMwZSWHNVYC5XODd7PvNDrDu
5MZJjkz4+6LbwwAvyew62meFN2QEsYbK2Brtbhze+IjE27FGWlSw4K3jlwa409MD
MTf4JU41ELaYY8G/LSNDJsBVhhkHzvXR9iCbXxNz3IL0dQDNj7h4LKhBy0q7hvqg
kDzwlmBO4WKSmCAuky44cXmd
-----END CERTIFICATE-----
subject=/CN=li190-250.members.linode.com
issuer=/CN=li190-250.members.linode.com
---
No client certificate CA names sent
---
SSL handshake has read 1714 bytes and written 637 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: NONE
Expansion: NONE
SSL-Session:
    Protocol  : SSLv3
    Cipher    : DHE-RSA-AES256-SHA
    Session-ID: C1D18BCBDE69A181D846C3AD9CB52C505410F972963F7E876721CAAF043C16FB
    Session-ID-ctx:
    Master-Key: 564107241150338B92A73C4E215D8D1CB951EC828364144AF5AD0F71BE0FFB44777064220F62C148AAB96F9C7C60972D
    Key-Arg   : None
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    Start Time: 1440011944
    Timeout   : 300 (sec)
    Verify return code: 18 (self signed certificate)
---
cluFn7wTiGryunymYOu4RcffSxQluehd
cluFn7wTiGryunymYOu4RcffSxQluehd
bandit16@melinda:~$ openssl s_client -connect localhost:31790
CONNECTED(00000003)
depth=0 CN = li190-250.members.linode.com
verify error:num=18:self signed certificate
verify return:1
depth=0 CN = li190-250.members.linode.com
verify return:1
---
Certificate chain
 0 s:/CN=li190-250.members.linode.com
   i:/CN=li190-250.members.linode.com
---
Server certificate
-----BEGIN CERTIFICATE-----
MIIC3jCCAcagAwIBAgIJAI5QiWZw4YHbMA0GCSqGSIb3DQEBCwUAMCcxJTAjBgNV
BAMTHGxpMTkwLTI1MC5tZW1iZXJzLmxpbm9kZS5jb20wHhcNMTQxMTE0MTAyODA0
WhcNMjQxMTExMTAyODA0WjAnMSUwIwYDVQQDExxsaTE5MC0yNTAubWVtYmVycy5s
aW5vZGUuY29tMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAsKmy9o5z
WU+1EH7Z3bB5TGQA+16zXDcEJy6tZWZ8CDrRyQXiahendp45BWUc/ZuLDo0+B3Wt
ZXjofmLw/F4fmR+8X1s1fQZX2dFt920qEm7LxqzWd0c7FdHiBwwRrwhkk+3cQpOB
TTGdLWEgpdmwwNZDTUdsDLzjDczPnju6T6p6ArTECztPbmTjfY4QIRtC6capL1Z+
yPJSQVAuAMEX1wTDWTGdm0VV7oW4F5cGZutf6QAP51jdhSyZuGilIPHbnj0l6Qc7
a7+OtEsEGi31aJ8KpRf7LNZ7DXCuoB3Hf75Pd6VjDgoOIagcH0NYqa75gEjBkGzs
ktLWykT7ag7fKwIDAQABow0wCzAJBgNVHRMEAjAAMA0GCSqGSIb3DQEBCwUAA4IB
AQCaZdUNAj8WDEKWdoU3LNXUBJlTJwiWBrh550PbHSQORcCz2K0kiMei1A4ojK2N
dMHFGAqAeUEaxtz92p2BoFpZasAtdSa3u63tBckFhfUolIS1TC7Cj51y19ysTeep
fGPFpuPCVqVPsruei8Z/iqn3bFIhQQdmumeePZQdPMwZSWHNVYC5XODd7PvNDrDu
5MZJjkz4+6LbwwAvyew62meFN2QEsYbK2Brtbhze+IjE27FGWlSw4K3jlwa409MD
MTf4JU41ELaYY8G/LSNDJsBVhhkHzvXR9iCbXxNz3IL0dQDNj7h4LKhBy0q7hvqg
kDzwlmBO4WKSmCAuky44cXmd
-----END CERTIFICATE-----
subject=/CN=li190-250.members.linode.com
issuer=/CN=li190-250.members.linode.com
---
No client certificate CA names sent
---
SSL handshake has read 1714 bytes and written 637 bytes
---
New, TLSv1/SSLv3, Cipher is DHE-RSA-AES256-SHA
Server public key is 2048 bit
Secure Renegotiation IS supported
Compression: NONE
Expansion: NONE
SSL-Session:
    Protocol  : SSLv3
    Cipher    : DHE-RSA-AES256-SHA
    Session-ID: 51350784DFB6CB86401CE36CF0647D206AF3E58EB4BBE357306B4B57E16B8DB6
    Session-ID-ctx:
    Master-Key: FA12EE208984E297C5F6D216DE9A94C74DCAC8CF999B13690774753AD0980B132C19F7AF71E3ED69D3CE405C001A0D69
    Key-Arg   : None
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    Start Time: 1440012120
    Timeout   : 300 (sec)
    Verify return code: 18 (self signed certificate)
---
cluFn7wTiGryunymYOu4RcffSxQluehd
Correct!
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----

read:errno=0
bandit16@melinda:/tmp$ mkdir sahan4321
bandit16@melinda:/tmp$ cd sahan4321
bandit16@melinda:/tmp/sahan4321$ touch key.private
bandit16@melinda:/tmp/sahan4321$ vi key.private
bandit16@melinda:/tmp/sahan4321$ chmod 600 key.private
bandit16@melinda:/tmp/sahan4321$ ssh -i key.private bandit17@localhost
Could not create directory '/home/bandit16/.ssh'.
The authenticity of host 'localhost (127.0.0.1)' can't be established.
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.
Are you sure you want to continue connecting (yes/no)? yes
</pre>
</p>
-
##Bandit Level  17 → Level 18
<p>
<pre>
bandit17@melinda:~$ ls
passwords.new  passwords.old
bandit17@melinda:~$ diff passwords.old passwords.new
42c42
< BS8bqB1kqkinKJjuxL6k072Qq9NRwQpR
---
> kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
bandit17@melinda:~$ exit
</pre>
</p>
-
##Bandit Level  18 → Level 19
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit18@bandit.labs.overthewire.org cat readme

This is the OverTheWire game server. More information on http://www.overthewire.org/wargames

Please note that wargame usernames are no longer level<X>, but wargamename<X>
e.g. vortex4, semtex2, ...

Note: at this moment, blacksun is not available.

bandit18@bandit.labs.overthewire.org's password:
X11 forwarding request failed on channel 0
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
</pre>
</p>
-
##Bandit Level  19 → Level 20
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit19@bandit.labs.overthewire.org
bandit19@bandit.labs.overthewire.org's password:IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
bandit19@melinda:~$ ls
bandit20-do
bandit19@melinda:~$ ./bandit20-do
Run a command as another user.
  Example: ./bandit20-do id
bandit19@melinda:~$ ./bandit20-do id
uid=11019(bandit19) gid=11019(bandit19) euid=11020(bandit20) groups=11020(bandit20),11019(bandit19)
bandit19@melinda:~$ ./bandit20-do whoami
bandit20
bandit19@melinda:~$ ./bandit20-do cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
bandit19@melinda:~$ exit
</pre>
</p>
-
##Bandit Level  20 → Level 21
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit20@bandit.labs.overthewire.org
bandit20@bandit.labs.overthewire.org's password:GbKksEFF4yrVs6il55v6gwY5aVje5f0j
bandit20@melinda:~$ ls
suconnect
bandit20@melinda:~$ ./ suconnect
-bash: ./: Is a directory
bandit20@melinda:~$ ./suconnect
Usage: ./suconnect <portnumber>
This program will connect to the given port on localhost using TCP. If it receives the correct password from the other side, the next password is transmitted back.
bandit20@melinda:~$ ./suconnect 30011
Read: GbKksEFF4yrVs6il55v6gwY5aVje5f0j
Password matches, sending next password
bandit20@melinda:~$ exit


bandit20@melinda:~$ nc -l 30011
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
</pre>
</p>
-
##Bandit Level  21 → Level 22
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit21@bandit.labs.overthewire.org
bandit21@bandit.labs.overthewire.org's password:gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
bandit21@melinda:~$ cd /etc/cron.d
bandit21@melinda:/etc/cron.d$ ls
behemoth4_cleanup  cronjob_bandit23       leviathan5_cleanup    natas-session-toucher  natas25_cleanup~  php5        semtex0-ppc  vortex0
cron-apt           cronjob_bandit24       manpage3_resetpw_job  natas-stats            natas26_cleanup   semtex0-32  semtex5      vortex20
cronjob_bandit22   cronjob_bandit24_root  melinda-stats         natas25_cleanup        natas27_cleanup   semtex0-64  sysstat
bandit21@melinda:/etc/cron.d$ cat cronjob_bandit22
* * * * * bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null

bandit21@melinda:/etc/cron.d$ cat /usr/bin/cronjob_bandit22.sh
#!/bin/bash
chmod 644 /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
cat /etc/bandit_pass/bandit22 > /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
bandit21@melinda:/etc/cron.d$ cat t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
cat: t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv: No such file or directory
bandit21@melinda:/etc/cron.d$ cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
Yk7owGAcWjwMVRwrTesJEwB7WVOiILL
bandit21@melinda:/etc/cron.d$ exit
</pre>
</p>
-
##Bandit Level  22 → Level 23
<p>
<pre>
[Sahan.Sahan-PC] ➤ ssh bandit22@bandit.labs.overthewire.org
bandit22@bandit.labs.overthewire.org's password:Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

bandit22@melinda:~$ cd /etc/cron.d/
bandit22@melinda:/etc/cron.d$ ls
behemoth4_cleanup  cronjob_bandit23       leviathan5_cleanup    natas-session-toucher  natas25_cleanup~  php5        semtex0-ppc  vortex0
cron-apt           cronjob_bandit24       manpage3_resetpw_job  natas-stats            natas26_cleanup   semtex0-32  semtex5      vortex20
cronjob_bandit22   cronjob_bandit24_root  melinda-stats         natas25_cleanup        natas27_cleanup   semtex0-64  sysstat
bandit22@melinda:/etc/cron.d$ cat cronjob_bandit23
* * * * * bandit23 /usr/bin/cronjob_bandit23.sh  &> /dev/null
bandit22@melinda:/etc/cron.d$ cat /usr/bin/cronjob_bandit23.sh
#!/bin/bash

myname=$(whoami)
mytarget=$(echo I am user $myname | md5sum | cut -d ' ' -f 1)

echo "Copying passwordfile /etc/bandit_pass/$myname to /tmp/$mytarget"

cat /etc/bandit_pass/$myname > /tmp/$mytarget

bandit22@melinda:/$ echo I am user bandit23 | md5sum | cut -d ' ' -f 1
8ca319486bfbbc3663ea0fbe81326349
bandit22@melinda:/$ cat tmp/8ca319486bfbbc3663ea0fbe81326349
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
bandit22@melinda:/$ exit
</pre>
</p>
-






