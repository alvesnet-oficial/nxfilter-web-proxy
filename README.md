# nxfilter-web-proxy

# Download:

ubuntu@localhost:~$ wget http://pub.nxfilter.org/nxfilter-4.5.2.5.deb

--2021-09-17 19:51:03--  http://pub.nxfilter.org/nxfilter-4.5.2.5.deb

Resolving pub.nxfilter.org (pub.nxfilter.org)... 68.66.205.245

Connecting to pub.nxfilter.org (pub.nxfilter.org)|68.66.205.245|:80... connected.

HTTP request sent, awaiting response... 200 OK

Length: 42060896 (40M) [application/octet-stream]


Saving to: ‘nxfilter-4.5.2.5.deb’



nxfilter-4.5.2.5.deb                                           100%[====================================================================================================================================================>]  40.11M  34.7MB/s    in 1.2s


2021-09-17 19:51:04 (34.7 MB/s) - ‘nxfilter-4.5.2.5.deb’ saved [42060896/42060896]


# Instalação:

ubuntu@localhost:~$ sudo dpkg -i nxfilter-4.5.2.5.deb

(Reading database ... 520267 files and directories currently installed.)

Preparing to unpack nxfilter-4.5.2.5.deb ...

Unpacking nxfilter (4.5.2.5) over (4.5.2.1) ...

Setting up nxfilter (4.5.2.5) ...

Processing triggers for ureadahead (0.100.0-21) ...

# Inciar:

ubuntu@localhost:/$ cd /nxfilter/

ubuntu@localhost:/nxfilter$ ls

backup  bin  conf  db  guipack  jahaslist  lib  license.txt  log  modified  nxd.ico  nxd.jar  nxwrapper.exe  prunsrv.exe  readme.txt  third-party-license.txt  tmp  tutorial.html  webapps

ubuntu@localhost:/nxfilter$ cd bin

ubuntu@localhost:/nxfilter/bin$ ls

admin.bat     cachecon.sh  cleanup.sh   ping.bat  reset-acl.bat  reset-pw.bat  shutdown.bat  startup.bat  tutorial.bat  update_sh.sh  version.sh
cachecon.bat  cleanup.bat  instsvc.bat  ping.sh   reset-acl.sh   reset-pw.sh   shutdown.sh   startup.sh   unstsvc.bat   version.bat

ubuntu@localhost:/nxfilter/bin$ ./startup.bat


