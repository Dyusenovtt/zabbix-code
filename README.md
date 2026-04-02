# zabbix-code
Linux myvm 6.1.0-44-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.1.164-1 (2026-03-09) x86_64

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
student1@myvm:~$ sudo su
root@myvm:/home/student1# cd
root@myvm:~# apt update
Get:1 http://mirror.yandex.ru/debian bookworm InRelease [151 kB]
Get:2 http://mirror.yandex.ru/debian bookworm-updates InRelease [55.4 kB]                     
Get:3 http://mirror.yandex.ru/debian bookworm-backports InRelease [59.4 kB]
Get:4 http://security.debian.org bookworm-security InRelease [48.0 kB]
Get:5 http://mirror.yandex.ru/debian bookworm/main Sources [9,495 kB]
Get:6 http://mirror.yandex.ru/debian bookworm/main amd64 Packages [8,792 kB]
Get:7 http://security.debian.org bookworm-security/main Sources [185 kB]          
Get:8 http://mirror.yandex.ru/debian bookworm/main Translation-en [6,108 kB]               
Get:9 http://security.debian.org bookworm-security/main amd64 Packages [294 kB]            
Get:10 http://security.debian.org bookworm-security/main Translation-en [179 kB]              
Get:11 http://mirror.yandex.ru/debian bookworm/main amd64 Contents (deb) [11.6 MB]   
Get:12 http://mirror.yandex.ru/debian bookworm/main all Contents (deb) [34.0 MB]
Get:13 http://mirror.yandex.ru/debian bookworm-updates/main Sources [3,288 B]
Get:14 http://mirror.yandex.ru/debian bookworm-updates/main amd64 Packages [6,924 B]
Get:15 http://mirror.yandex.ru/debian bookworm-updates/main Translation-en [5,448 B]
Get:16 http://mirror.yandex.ru/debian bookworm-updates/main all Contents (deb) [46.3 kB]
Get:17 http://mirror.yandex.ru/debian bookworm-updates/main amd64 Contents (deb) [17.1 kB]
Get:18 http://mirror.yandex.ru/debian bookworm-backports/main Sources [299 kB]
Get:19 http://mirror.yandex.ru/debian bookworm-backports/main amd64 Packages [305 kB]
Get:20 http://mirror.yandex.ru/debian bookworm-backports/main Translation-en [257 kB]
Get:21 http://mirror.yandex.ru/debian bookworm-backports/main all Contents (deb) [4,820 kB]
Get:22 http://mirror.yandex.ru/debian bookworm-backports/main amd64 Contents (deb) [2,142 kB]
Fetched 78.9 MB in 7s (10.6 MB/s)                                                                                    
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
5 packages can be upgraded. Run 'apt list --upgradable' to see them.
N: Repository 'Debian bookworm' changed its 'firmware component' value from 'non-free' to 'non-free-firmware'
N: More information about this can be found online in the Release notes at: https://www.debian.org/releases/bookworm/amd64/release-notes/ch-information.html#non-free-split
root@myvm:~# apt update
Hit:1 http://mirror.yandex.ru/debian bookworm InRelease
Hit:2 http://mirror.yandex.ru/debian bookworm-updates InRelease
Hit:3 http://mirror.yandex.ru/debian bookworm-backports InRelease
Hit:4 http://security.debian.org bookworm-security InRelease 
Reading package lists... Done                                
Building dependency tree... Done
Reading state information... Done
5 packages can be upgraded. Run 'apt list --upgradable' to see them.
N: Repository 'Debian bookworm' changed its 'firmware component' value from 'non-free' to 'non-free-firmware'
N: More information about this can be found online in the Release notes at: https://www.debian.org/releases/bookworm/amd64/release-notes/ch-information.html#non-free-split
root@myvm:~# apt install mc
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  mailcap mc-data
Suggested packages:
  arj catdvi | texlive-binaries dbview djvulibre-bin epub-utils gv imagemagick libaspell-dev links | w3m | lynx
  odt2txt poppler-utils python python-boto python-tz unar wimtools xpdf | pdf-viewer zip
The following NEW packages will be installed:
  mailcap mc mc-data
0 upgraded, 3 newly installed, 0 to remove and 5 not upgraded.
Need to get 1,900 kB of archives.
After this operation, 7,977 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://mirror.yandex.ru/debian bookworm/main amd64 mailcap all 3.70+nmu1 [32.0 kB]
Get:2 http://mirror.yandex.ru/debian bookworm/main amd64 mc-data all 3:4.8.29-2 [1,346 kB]
Get:3 http://mirror.yandex.ru/debian bookworm/main amd64 mc amd64 3:4.8.29-2 [522 kB]
Fetched 1,900 kB in 0s (9,766 kB/s)
Selecting previously unselected package mailcap.
(Reading database ... 34799 files and directories currently installed.)
Preparing to unpack .../mailcap_3.70+nmu1_all.deb ...
Unpacking mailcap (3.70+nmu1) ...
Selecting previously unselected package mc-data.
Preparing to unpack .../mc-data_3%3a4.8.29-2_all.deb ...
Unpacking mc-data (3:4.8.29-2) ...
Selecting previously unselected package mc.
Preparing to unpack .../mc_3%3a4.8.29-2_amd64.deb ...
Unpacking mc (3:4.8.29-2) ...
Setting up mc-data (3:4.8.29-2) ...
Setting up mailcap (3.70+nmu1) ...
Setting up mc (3:4.8.29-2) ...
root@myvm:~# Linux myvm 6.1.0-44-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.1.164-1 (2026-03-09) x86_64

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Thu Apr  2 06:34:32 2026 from 46.61.147.254
student1@myvm:~$ wget https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release_latest_6.0+debian12_all.deb
--2026-04-02 09:11:02--  https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release_latest_6.0+debian12_all.deb
Resolving repo.zabbix.com (repo.zabbix.com)... 178.128.6.101, 2604:a880:2:d0::2062:d001
Connecting to repo.zabbix.com (repo.zabbix.com)|178.128.6.101|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 3448 (3.4K) [application/octet-stream]
Saving to: ‘zabbix-release_latest_6.0+debian12_all.deb’

zabbix-release_latest 100%[=========================>]   3.37K  --.-KB/s    in 0s      

2026-04-02 09:11:10 (133 MB/s) - ‘zabbix-release_latest_6.0+debian12_all.deb’ saved [3448/3448]

student1@myvm:~$ dpkg -i zabbix-release_latest_6.0+debian12_all.deb
dpkg: error: requested operation requires superuser privilege
student1@myvm:~$ sudo dpkg -i zabbix-release_latest_6.0+debian12_all.deb
Selecting previously unselected package zabbix-release.
(Reading database ... 35216 files and directories currently installed.)
Preparing to unpack zabbix-release_latest_6.0+debian12_all.deb ...
Unpacking zabbix-release (1:6.0-5+debian12) ...
Setting up zabbix-release (1:6.0-5+debian12) ...
student1@myvm:~$ sudo apt update
Hit:1 http://mirror.yandex.ru/debian bookworm InRelease
Hit:2 http://mirror.yandex.ru/debian bookworm-updates InRelease                        
Hit:3 http://mirror.yandex.ru/debian bookworm-backports InRelease                      
Hit:4 http://security.debian.org bookworm-security InRelease                           
Get:5 https://repo.zabbix.com/zabbix/6.0/debian bookworm InRelease [2,883 B]           
Get:6 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main Sources [37.4 kB]
Get:7 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main all Packages [16.2 kB]
Get:8 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main amd64 Packages [84.2 kB]
Fetched 141 kB in 2s (56.7 kB/s)    
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
5 packages can be upgraded. Run 'apt list --upgradable' to see them.
N: Repository 'Debian bookworm' changed its 'firmware component' value from 'non-free' to 'non-free-firmware'
N: More information about this can be found online in the Release notes at: https://www.debian.org/releases/bookworm/amd64/release-notes/ch-information.html#non-free-split
student1@myvm:~$ apt install zabbix-server-pgsql zabbix-frontend-php php8.2-pgsql zabbix-apache-conf zabbix-sql-scripts zabbix-agent
E: Could not open lock file /var/lib/dpkg/lock-frontend - open (13: Permission denied)
E: Unable to acquire the dpkg frontend lock (/var/lib/dpkg/lock-frontend), are you root?
student1@myvm:~$ sudo apt install zabbix-server-pgsql zabbix-frontend-php php8.2-pgsql z
abbix-apache-conf zabbix-sql-scripts zabbix-agent
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  apache2 apache2-bin apache2-data apache2-utils fontconfig-config fonts-dejavu
  fonts-dejavu-core fonts-dejavu-extra fping libabsl20220623 libaom3
  libapache2-mod-php libapache2-mod-php8.2 libapr1 libaprutil1 libaprutil1-dbd-sqlite3
  libaprutil1-ldap libavif15 libdav1d6 libde265-0 libdeflate0 libevent-2.1-7
  libfontconfig1 libgav1-1 libgd3 libheif1 libjbig0 libjpeg62-turbo liblerc4 libltdl7
  liblua5.3-0 libmodbus5 libodbc2 libonig5 libopenipmi0 libpq5 librav1e0
  libsensors-config libsensors5 libsnmp-base libsnmp40 libssh-4 libsvtav1enc1 libtiff6
  libwebp7 libx265-199 libxpm4 libxslt1.1 libyuv0 php-bcmath php-common php-gd
  php-ldap php-mbstring php-xml php8.2-bcmath php8.2-cli php8.2-common php8.2-gd
  php8.2-ldap php8.2-mbstring php8.2-opcache php8.2-readline php8.2-xml psmisc snmpd
  ssl-cert
Suggested packages:
  apache2-doc apache2-suexec-pristine | apache2-suexec-custom www-browser php-pear
  libgd-tools odbc-postgresql tdsodbc lm-sensors snmp-mibs-downloader snmptrapd
  zabbix-nginx-conf postgresql-client postgresql
The following NEW packages will be installed:
  apache2 apache2-bin apache2-data apache2-utils fontconfig-config fonts-dejavu
  fonts-dejavu-core fonts-dejavu-extra fping libabsl20220623 libaom3
  libapache2-mod-php libapache2-mod-php8.2 libapr1 libaprutil1 libaprutil1-dbd-sqlite3
  libaprutil1-ldap libavif15 libdav1d6 libde265-0 libdeflate0 libevent-2.1-7
  libfontconfig1 libgav1-1 libgd3 libheif1 libjbig0 libjpeg62-turbo liblerc4 libltdl7
  liblua5.3-0 libmodbus5 libodbc2 libonig5 libopenipmi0 libpq5 librav1e0
  libsensors-config libsensors5 libsnmp-base libsnmp40 libssh-4 libsvtav1enc1 libtiff6
  libwebp7 libx265-199 libxpm4 libxslt1.1 libyuv0 php-bcmath php-common php-gd
  php-ldap php-mbstring php-xml php8.2-bcmath php8.2-cli php8.2-common php8.2-gd
  php8.2-ldap php8.2-mbstring php8.2-opcache php8.2-pgsql php8.2-readline php8.2-xml
  psmisc snmpd ssl-cert zabbix-agent zabbix-apache-conf zabbix-frontend-php
  zabbix-server-pgsql zabbix-sql-scripts
0 upgraded, 73 newly installed, 0 to remove and 5 not upgraded.
Need to get 45.3 MB of archives.
After this operation, 155 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://mirror.yandex.ru/debian bookworm/main amd64 libapr1 amd64 1.7.2-3+deb12u1 [102 kB]
Get:2 http://mirror.yandex.ru/debian bookworm/main amd64 libaprutil1 amd64 1.6.3-1 [87.8 kB]
Get:3 http://mirror.yandex.ru/debian bookworm/main amd64 libaprutil1-dbd-sqlite3 amd64 1.6.3-1 [13.6 kB]
Get:4 http://mirror.yandex.ru/debian bookworm/main amd64 libaprutil1-ldap amd64 1.6.3-1 [11.8 kB]
Get:5 http://mirror.yandex.ru/debian bookworm/main amd64 liblua5.3-0 amd64 5.3.6-2 [123 kB]
Get:6 http://security.debian.org bookworm-security/main amd64 libsnmp-base all 5.9.3+dfsg-2+deb12u1 [1,753 kB]
Get:7 http://mirror.yandex.ru/debian bookworm/main amd64 apache2-bin amd64 2.4.66-1~deb12u1 [1,400 kB]
Get:8 http://mirror.yandex.ru/debian bookworm/main amd64 apache2-data all 2.4.66-1~deb12u1 [160 kB]
Get:9 http://mirror.yandex.ru/debian bookworm/main amd64 apache2-utils amd64 2.4.66-1~deb12u1 [215 kB]
Get:10 http://mirror.yandex.ru/debian bookworm/main amd64 apache2 amd64 2.4.66-1~deb12u1 [229 kB]
Get:11 http://mirror.yandex.ru/debian bookworm/main amd64 libsensors-config all 1:3.6.0-7.1 [14.3 kB]
Get:12 http://mirror.yandex.ru/debian bookworm/main amd64 libsensors5 amd64 1:3.6.0-7.1 [34.2 kB]
Get:13 http://mirror.yandex.ru/debian bookworm/main amd64 libevent-2.1-7 amd64 2.1.12-stable-8 [180 kB]
Get:14 http://mirror.yandex.ru/debian bookworm/main amd64 libltdl7 amd64 2.4.7-7~deb12u1 [393 kB]
Get:15 http://mirror.yandex.ru/debian bookworm/main amd64 libodbc2 amd64 2.3.11-2+deb12u1 [150 kB]
Get:16 http://mirror.yandex.ru/debian bookworm/main amd64 libopenipmi0 amd64 2.0.33-1+b1 [551 kB]
Get:17 http://mirror.yandex.ru/debian bookworm/main amd64 libssh-4 amd64 0.10.6-0+deb12u2 [189 kB]
Get:18 http://mirror.yandex.ru/debian bookworm/main amd64 fping amd64 5.1-1 [40.7 kB]  
Get:19 http://mirror.yandex.ru/debian bookworm/main amd64 fonts-dejavu-core all 2.37-6 [1,068 kB]
Get:20 http://security.debian.org bookworm-security/main amd64 libsnmp40 amd64 5.9.3+dfsg-2+deb12u1 [2,557 kB]
Get:21 http://mirror.yandex.ru/debian bookworm/main amd64 fontconfig-config amd64 2.14.1-4 [315 kB]
Get:22 http://security.debian.org bookworm-security/main amd64 snmpd amd64 5.9.3+dfsg-2+deb12u1 [57.5 kB]
Get:23 http://mirror.yandex.ru/debian bookworm/main amd64 fonts-dejavu-extra all 2.37-6 [1,985 kB]
Get:24 http://security.debian.org bookworm-security/main amd64 libpq5 amd64 15.16-0+deb12u1 [196 kB]
Get:25 http://security.debian.org bookworm-security/main amd64 php8.2-common amd64 8.2.30-1~deb12u1 [690 kB]
Get:26 http://security.debian.org bookworm-security/main amd64 php8.2-opcache amd64 8.2.30-1~deb12u1 [346 kB]
Get:27 http://security.debian.org bookworm-security/main amd64 php8.2-readline amd64 8.2.30-1~deb12u1 [12.4 kB]
Get:28 http://security.debian.org bookworm-security/main amd64 php8.2-cli amd64 8.2.30-1~deb12u1 [1,740 kB]
Get:29 http://mirror.yandex.ru/debian bookworm/main amd64 fonts-dejavu all 2.37-6 [27.8 kB]
Get:30 http://security.debian.org bookworm-security/main amd64 libapache2-mod-php8.2 amd64 8.2.30-1~deb12u1 [1,680 kB]
Get:31 http://security.debian.org bookworm-security/main amd64 php8.2-bcmath amd64 8.2.30-1~deb12u1 [15.3 kB]
Get:32 http://mirror.yandex.ru/debian bookworm/main amd64 libabsl20220623 amd64 20220623.1-1+deb12u2 [391 kB]
Get:33 http://security.debian.org bookworm-security/main amd64 php8.2-gd amd64 8.2.30-1~deb12u1 [28.9 kB]
Get:34 http://security.debian.org bookworm-security/main amd64 php8.2-ldap amd64 8.2.30-1~deb12u1 [31.5 kB]
Get:35 http://security.debian.org bookworm-security/main amd64 php8.2-mbstring amd64 8.2.30-1~deb12u1 [443 kB]
Get:36 http://security.debian.org bookworm-security/main amd64 php8.2-xml amd64 8.2.30-1~deb12u1 [113 kB]
Get:37 http://security.debian.org bookworm-security/main amd64 php8.2-pgsql amd64 8.2.30-1~deb12u1 [58.1 kB]
Get:38 http://mirror.yandex.ru/debian bookworm/main amd64 libaom3 amd64 3.6.0-1+deb12u2 [1,850 kB]
Get:39 http://mirror.yandex.ru/debian bookworm/main amd64 psmisc amd64 23.6-1 [259 kB]
Get:40 http://mirror.yandex.ru/debian bookworm/main amd64 php-common all 2:93 [13.1 kB]
Get:41 http://mirror.yandex.ru/debian bookworm/main amd64 libapache2-mod-php all 2:8.2+93 [3,764 B]
Get:42 http://mirror.yandex.ru/debian bookworm/main amd64 libdav1d6 amd64 1.0.0-2+deb12u1 [513 kB]
Get:43 http://mirror.yandex.ru/debian bookworm/main amd64 libgav1-1 amd64 0.18.0-1+b1 [332 kB]
Get:44 http://mirror.yandex.ru/debian bookworm/main amd64 librav1e0 amd64 0.5.1-6 [763 kB]
Get:45 http://mirror.yandex.ru/debian bookworm/main amd64 libsvtav1enc1 amd64 1.4.1+dfsg-1 [2,121 kB]
Get:46 http://mirror.yandex.ru/debian bookworm/main amd64 libjpeg62-turbo amd64 1:2.1.5-2 [166 kB]
Get:47 http://mirror.yandex.ru/debian bookworm/main amd64 libyuv0 amd64 0.0~git20230123.b2528b0-1 [168 kB]
Get:48 http://mirror.yandex.ru/debian bookworm/main amd64 libavif15 amd64 0.11.1-1+deb12u1 [94.4 kB]
Get:49 http://mirror.yandex.ru/debian bookworm/main amd64 libde265-0 amd64 1.0.11-1+deb12u2 [185 kB]
Get:50 http://mirror.yandex.ru/debian bookworm/main amd64 libdeflate0 amd64 1.14-1 [61.4 kB]
Get:51 http://mirror.yandex.ru/debian bookworm/main amd64 libfontconfig1 amd64 2.14.1-4 [386 kB]
Get:52 http://mirror.yandex.ru/debian bookworm/main amd64 libx265-199 amd64 3.5-2+b1 [1,150 kB]
Get:53 http://mirror.yandex.ru/debian bookworm/main amd64 libheif1 amd64 1.15.1-1+deb12u1 [215 kB]
Get:54 http://mirror.yandex.ru/debian bookworm/main amd64 libjbig0 amd64 2.1-6.1 [31.7 kB]
Get:55 http://mirror.yandex.ru/debian bookworm/main amd64 liblerc4 amd64 4.0.0+ds-2 [170 kB]
Get:56 http://mirror.yandex.ru/debian bookworm/main amd64 libwebp7 amd64 1.2.4-0.2+deb12u1 [286 kB]
Get:57 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main amd64 zabbix-server-pgsql amd64 1:6.0.45-1+debian12 [1,755 kB]
Get:58 http://mirror.yandex.ru/debian bookworm/main amd64 libtiff6 amd64 4.5.0-6+deb12u3 [316 kB]
Get:59 http://mirror.yandex.ru/debian bookworm/main amd64 libxpm4 amd64 1:3.5.12-1.1+deb12u1 [48.6 kB]
Get:60 http://mirror.yandex.ru/debian bookworm/main amd64 libgd3 amd64 2.3.3-9 [124 kB]
Get:61 http://mirror.yandex.ru/debian bookworm/main amd64 libmodbus5 amd64 3.1.6-2.1 [31.3 kB]
Get:62 http://mirror.yandex.ru/debian bookworm/main amd64 libonig5 amd64 6.9.8-1 [188 kB]
Get:63 http://mirror.yandex.ru/debian bookworm/main amd64 libxslt1.1 amd64 1.1.35-1+deb12u3 [231 kB]
Get:64 http://mirror.yandex.ru/debian bookworm/main amd64 php-bcmath all 2:8.2+93 [3,664 B]
Get:65 http://mirror.yandex.ru/debian bookworm/main amd64 php-gd all 2:8.2+93 [3,648 B]
Get:66 http://mirror.yandex.ru/debian bookworm/main amd64 php-ldap all 2:8.2+93 [3,652 B]
Get:67 http://mirror.yandex.ru/debian bookworm/main amd64 php-mbstring all 2:8.2+93 [3,664 B]
Get:68 http://mirror.yandex.ru/debian bookworm/main amd64 php-xml all 2:8.2+93 [3,672 B]
Get:69 http://mirror.yandex.ru/debian bookworm/main amd64 ssl-cert all 1.1.2 [21.1 kB]
Get:70 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main amd64 zabbix-agent amd64 1:6.0.45-1+debian12 [657 kB]
Get:71 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main all zabbix-frontend-php all 1:6.0.45-1+debian12 [7,490 kB]
Get:72 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main all zabbix-apache-conf all 1:6.0.45-1+debian12 [408 kB]
Get:73 https://repo.zabbix.com/zabbix/6.0/debian bookworm/main all zabbix-sql-scripts all 1:6.0.45-1+debian12 [7,850 kB]
Fetched 45.3 MB in 13s (3,383 kB/s)                                                    
Extracting templates from packages: 100%
Preconfiguring packages ...
Selecting previously unselected package libapr1:amd64.
(Reading database ... 35222 files and directories currently installed.)
Preparing to unpack .../00-libapr1_1.7.2-3+deb12u1_amd64.deb ...
Unpacking libapr1:amd64 (1.7.2-3+deb12u1) ...
Selecting previously unselected package libaprutil1:amd64.
Preparing to unpack .../01-libaprutil1_1.6.3-1_amd64.deb ...
Unpacking libaprutil1:amd64 (1.6.3-1) ...
Selecting previously unselected package libaprutil1-dbd-sqlite3:amd64.
Preparing to unpack .../02-libaprutil1-dbd-sqlite3_1.6.3-1_amd64.deb ...
Unpacking libaprutil1-dbd-sqlite3:amd64 (1.6.3-1) ...
Selecting previously unselected package libaprutil1-ldap:amd64.
Preparing to unpack .../03-libaprutil1-ldap_1.6.3-1_amd64.deb ...
Unpacking libaprutil1-ldap:amd64 (1.6.3-1) ...
Selecting previously unselected package liblua5.3-0:amd64.
Preparing to unpack .../04-liblua5.3-0_5.3.6-2_amd64.deb ...
Unpacking liblua5.3-0:amd64 (5.3.6-2) ...
Selecting previously unselected package apache2-bin.
Preparing to unpack .../05-apache2-bin_2.4.66-1~deb12u1_amd64.deb ...
Unpacking apache2-bin (2.4.66-1~deb12u1) ...
Selecting previously unselected package apache2-data.
Preparing to unpack .../06-apache2-data_2.4.66-1~deb12u1_all.deb ...
Unpacking apache2-data (2.4.66-1~deb12u1) ...
Selecting previously unselected package apache2-utils.
Preparing to unpack .../07-apache2-utils_2.4.66-1~deb12u1_amd64.deb ...
Unpacking apache2-utils (2.4.66-1~deb12u1) ...
Selecting previously unselected package apache2.
Preparing to unpack .../08-apache2_2.4.66-1~deb12u1_amd64.deb ...
Unpacking apache2 (2.4.66-1~deb12u1) ...
Selecting previously unselected package libsensors-config.
Preparing to unpack .../09-libsensors-config_1%3a3.6.0-7.1_all.deb ...
Unpacking libsensors-config (1:3.6.0-7.1) ...
Selecting previously unselected package libsensors5:amd64.
Preparing to unpack .../10-libsensors5_1%3a3.6.0-7.1_amd64.deb ...
Unpacking libsensors5:amd64 (1:3.6.0-7.1) ...
Selecting previously unselected package libsnmp-base.
Preparing to unpack .../11-libsnmp-base_5.9.3+dfsg-2+deb12u1_all.deb ...
Unpacking libsnmp-base (5.9.3+dfsg-2+deb12u1) ...
Selecting previously unselected package libsnmp40:amd64.
Preparing to unpack .../12-libsnmp40_5.9.3+dfsg-2+deb12u1_amd64.deb ...
Unpacking libsnmp40:amd64 (5.9.3+dfsg-2+deb12u1) ...
Selecting previously unselected package snmpd.
Preparing to unpack .../13-snmpd_5.9.3+dfsg-2+deb12u1_amd64.deb ...
Unpacking snmpd (5.9.3+dfsg-2+deb12u1) ...
Selecting previously unselected package libevent-2.1-7:amd64.
Preparing to unpack .../14-libevent-2.1-7_2.1.12-stable-8_amd64.deb ...
Unpacking libevent-2.1-7:amd64 (2.1.12-stable-8) ...
Selecting previously unselected package libltdl7:amd64.
Preparing to unpack .../15-libltdl7_2.4.7-7~deb12u1_amd64.deb ...
Unpacking libltdl7:amd64 (2.4.7-7~deb12u1) ...
Selecting previously unselected package libodbc2:amd64.
Preparing to unpack .../16-libodbc2_2.3.11-2+deb12u1_amd64.deb ...
Unpacking libodbc2:amd64 (2.3.11-2+deb12u1) ...
Selecting previously unselected package libopenipmi0.
Preparing to unpack .../17-libopenipmi0_2.0.33-1+b1_amd64.deb ...
Unpacking libopenipmi0 (2.0.33-1+b1) ...
Selecting previously unselected package libpq5:amd64.
Preparing to unpack .../18-libpq5_15.16-0+deb12u1_amd64.deb ...
Unpacking libpq5:amd64 (15.16-0+deb12u1) ...
Selecting previously unselected package libssh-4:amd64.
Preparing to unpack .../19-libssh-4_0.10.6-0+deb12u2_amd64.deb ...
Unpacking libssh-4:amd64 (0.10.6-0+deb12u2) ...
Selecting previously unselected package fping.
Preparing to unpack .../20-fping_5.1-1_amd64.deb ...
Unpacking fping (5.1-1) ...
Selecting previously unselected package zabbix-server-pgsql.
Preparing to unpack .../21-zabbix-server-pgsql_1%3a6.0.45-1+debian12_amd64.deb ...
Unpacking zabbix-server-pgsql (1:6.0.45-1+debian12) ...
Selecting previously unselected package fonts-dejavu-core.
Preparing to unpack .../22-fonts-dejavu-core_2.37-6_all.deb ...
Unpacking fonts-dejavu-core (2.37-6) ...
Selecting previously unselected package fontconfig-config.
Preparing to unpack .../23-fontconfig-config_2.14.1-4_amd64.deb ...
Unpacking fontconfig-config (2.14.1-4) ...
Selecting previously unselected package fonts-dejavu-extra.
Preparing to unpack .../24-fonts-dejavu-extra_2.37-6_all.deb ...
Unpacking fonts-dejavu-extra (2.37-6) ...
Selecting previously unselected package fonts-dejavu.
Preparing to unpack .../25-fonts-dejavu_2.37-6_all.deb ...
Unpacking fonts-dejavu (2.37-6) ...
Selecting previously unselected package libabsl20220623:amd64.
Preparing to unpack .../26-libabsl20220623_20220623.1-1+deb12u2_amd64.deb ...
Unpacking libabsl20220623:amd64 (20220623.1-1+deb12u2) ...
Selecting previously unselected package libaom3:amd64.
Preparing to unpack .../27-libaom3_3.6.0-1+deb12u2_amd64.deb ...
Unpacking libaom3:amd64 (3.6.0-1+deb12u2) ...
Selecting previously unselected package psmisc.
Preparing to unpack .../28-psmisc_23.6-1_amd64.deb ...
Unpacking psmisc (23.6-1) ...
Selecting previously unselected package php-common.
Preparing to unpack .../29-php-common_2%3a93_all.deb ...
Unpacking php-common (2:93) ...
Selecting previously unselected package php8.2-common.
Preparing to unpack .../30-php8.2-common_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-common (8.2.30-1~deb12u1) ...
Selecting previously unselected package php8.2-opcache.
Preparing to unpack .../31-php8.2-opcache_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-opcache (8.2.30-1~deb12u1) ...
Selecting previously unselected package php8.2-readline.
Preparing to unpack .../32-php8.2-readline_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-readline (8.2.30-1~deb12u1) ...
Selecting previously unselected package php8.2-cli.
Preparing to unpack .../33-php8.2-cli_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-cli (8.2.30-1~deb12u1) ...
Selecting previously unselected package libapache2-mod-php8.2.
Preparing to unpack .../34-libapache2-mod-php8.2_8.2.30-1~deb12u1_amd64.deb ...
Unpacking libapache2-mod-php8.2 (8.2.30-1~deb12u1) ...
Selecting previously unselected package libapache2-mod-php.
Preparing to unpack .../35-libapache2-mod-php_2%3a8.2+93_all.deb ...
Unpacking libapache2-mod-php (2:8.2+93) ...
Selecting previously unselected package libdav1d6:amd64.
Preparing to unpack .../36-libdav1d6_1.0.0-2+deb12u1_amd64.deb ...
Unpacking libdav1d6:amd64 (1.0.0-2+deb12u1) ...
Selecting previously unselected package libgav1-1:amd64.
Preparing to unpack .../37-libgav1-1_0.18.0-1+b1_amd64.deb ...
Unpacking libgav1-1:amd64 (0.18.0-1+b1) ...
Selecting previously unselected package librav1e0:amd64.
Preparing to unpack .../38-librav1e0_0.5.1-6_amd64.deb ...
Unpacking librav1e0:amd64 (0.5.1-6) ...
Selecting previously unselected package libsvtav1enc1:amd64.
Preparing to unpack .../39-libsvtav1enc1_1.4.1+dfsg-1_amd64.deb ...
Unpacking libsvtav1enc1:amd64 (1.4.1+dfsg-1) ...
Selecting previously unselected package libjpeg62-turbo:amd64.
Preparing to unpack .../40-libjpeg62-turbo_1%3a2.1.5-2_amd64.deb ...
Unpacking libjpeg62-turbo:amd64 (1:2.1.5-2) ...
Selecting previously unselected package libyuv0:amd64.
Preparing to unpack .../41-libyuv0_0.0~git20230123.b2528b0-1_amd64.deb ...
Unpacking libyuv0:amd64 (0.0~git20230123.b2528b0-1) ...
Selecting previously unselected package libavif15:amd64.
Preparing to unpack .../42-libavif15_0.11.1-1+deb12u1_amd64.deb ...
Unpacking libavif15:amd64 (0.11.1-1+deb12u1) ...
Selecting previously unselected package libde265-0:amd64.
Preparing to unpack .../43-libde265-0_1.0.11-1+deb12u2_amd64.deb ...
Unpacking libde265-0:amd64 (1.0.11-1+deb12u2) ...
Selecting previously unselected package libdeflate0:amd64.
Preparing to unpack .../44-libdeflate0_1.14-1_amd64.deb ...
Unpacking libdeflate0:amd64 (1.14-1) ...
Selecting previously unselected package libfontconfig1:amd64.
Preparing to unpack .../45-libfontconfig1_2.14.1-4_amd64.deb ...
Unpacking libfontconfig1:amd64 (2.14.1-4) ...
Selecting previously unselected package libx265-199:amd64.
Preparing to unpack .../46-libx265-199_3.5-2+b1_amd64.deb ...
Unpacking libx265-199:amd64 (3.5-2+b1) ...
Selecting previously unselected package libheif1:amd64.
Preparing to unpack .../47-libheif1_1.15.1-1+deb12u1_amd64.deb ...
Unpacking libheif1:amd64 (1.15.1-1+deb12u1) ...
Selecting previously unselected package libjbig0:amd64.
Preparing to unpack .../48-libjbig0_2.1-6.1_amd64.deb ...
Unpacking libjbig0:amd64 (2.1-6.1) ...
Selecting previously unselected package liblerc4:amd64.
Preparing to unpack .../49-liblerc4_4.0.0+ds-2_amd64.deb ...
Unpacking liblerc4:amd64 (4.0.0+ds-2) ...
Selecting previously unselected package libwebp7:amd64.
Preparing to unpack .../50-libwebp7_1.2.4-0.2+deb12u1_amd64.deb ...
Unpacking libwebp7:amd64 (1.2.4-0.2+deb12u1) ...
Selecting previously unselected package libtiff6:amd64.
Preparing to unpack .../51-libtiff6_4.5.0-6+deb12u3_amd64.deb ...
Unpacking libtiff6:amd64 (4.5.0-6+deb12u3) ...
Selecting previously unselected package libxpm4:amd64.
Preparing to unpack .../52-libxpm4_1%3a3.5.12-1.1+deb12u1_amd64.deb ...
Unpacking libxpm4:amd64 (1:3.5.12-1.1+deb12u1) ...
Selecting previously unselected package libgd3:amd64.
Preparing to unpack .../53-libgd3_2.3.3-9_amd64.deb ...
Unpacking libgd3:amd64 (2.3.3-9) ...
Selecting previously unselected package libmodbus5:amd64.
Preparing to unpack .../54-libmodbus5_3.1.6-2.1_amd64.deb ...
Unpacking libmodbus5:amd64 (3.1.6-2.1) ...
Selecting previously unselected package libonig5:amd64.
Preparing to unpack .../55-libonig5_6.9.8-1_amd64.deb ...
Unpacking libonig5:amd64 (6.9.8-1) ...
Selecting previously unselected package libxslt1.1:amd64.
Preparing to unpack .../56-libxslt1.1_1.1.35-1+deb12u3_amd64.deb ...
Unpacking libxslt1.1:amd64 (1.1.35-1+deb12u3) ...
Selecting previously unselected package php8.2-bcmath.
Preparing to unpack .../57-php8.2-bcmath_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-bcmath (8.2.30-1~deb12u1) ...
Selecting previously unselected package php-bcmath.
Preparing to unpack .../58-php-bcmath_2%3a8.2+93_all.deb ...
Unpacking php-bcmath (2:8.2+93) ...
Selecting previously unselected package php8.2-gd.
Preparing to unpack .../59-php8.2-gd_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-gd (8.2.30-1~deb12u1) ...
Selecting previously unselected package php-gd.
Preparing to unpack .../60-php-gd_2%3a8.2+93_all.deb ...
Unpacking php-gd (2:8.2+93) ...
Selecting previously unselected package php8.2-ldap.
Preparing to unpack .../61-php8.2-ldap_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-ldap (8.2.30-1~deb12u1) ...
Selecting previously unselected package php-ldap.
Preparing to unpack .../62-php-ldap_2%3a8.2+93_all.deb ...
Unpacking php-ldap (2:8.2+93) ...
Selecting previously unselected package php8.2-mbstring.
Preparing to unpack .../63-php8.2-mbstring_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-mbstring (8.2.30-1~deb12u1) ...
Selecting previously unselected package php-mbstring.
Preparing to unpack .../64-php-mbstring_2%3a8.2+93_all.deb ...
Unpacking php-mbstring (2:8.2+93) ...
Selecting previously unselected package php8.2-xml.
Preparing to unpack .../65-php8.2-xml_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-xml (8.2.30-1~deb12u1) ...
Selecting previously unselected package php-xml.
Preparing to unpack .../66-php-xml_2%3a8.2+93_all.deb ...
Unpacking php-xml (2:8.2+93) ...
Selecting previously unselected package php8.2-pgsql.
Preparing to unpack .../67-php8.2-pgsql_8.2.30-1~deb12u1_amd64.deb ...
Unpacking php8.2-pgsql (8.2.30-1~deb12u1) ...
Selecting previously unselected package ssl-cert.
Preparing to unpack .../68-ssl-cert_1.1.2_all.deb ...
Unpacking ssl-cert (1.1.2) ...
Selecting previously unselected package zabbix-agent.
Preparing to unpack .../69-zabbix-agent_1%3a6.0.45-1+debian12_amd64.deb ...
Unpacking zabbix-agent (1:6.0.45-1+debian12) ...
Selecting previously unselected package zabbix-frontend-php.
Preparing to unpack .../70-zabbix-frontend-php_1%3a6.0.45-1+debian12_all.deb ...
Unpacking zabbix-frontend-php (1:6.0.45-1+debian12) ...
Selecting previously unselected package zabbix-apache-conf.
Preparing to unpack .../71-zabbix-apache-conf_1%3a6.0.45-1+debian12_all.deb ...
Unpacking zabbix-apache-conf (1:6.0.45-1+debian12) ...
Selecting previously unselected package zabbix-sql-scripts.
Preparing to unpack .../72-zabbix-sql-scripts_1%3a6.0.45-1+debian12_all.deb ...
Unpacking zabbix-sql-scripts (1:6.0.45-1+debian12) ...
Setting up libaom3:amd64 (3.6.0-1+deb12u2) ...
Setting up libabsl20220623:amd64 (20220623.1-1+deb12u2) ...
Setting up libmodbus5:amd64 (3.1.6-2.1) ...
Setting up liblerc4:amd64 (4.0.0+ds-2) ...
Setting up libxpm4:amd64 (1:3.5.12-1.1+deb12u1) ...
Setting up zabbix-sql-scripts (1:6.0.45-1+debian12) ...
Setting up psmisc (23.6-1) ...
Setting up libsnmp-base (5.9.3+dfsg-2+deb12u1) ...
Setting up libsensors-config (1:3.6.0-7.1) ...
Setting up libpq5:amd64 (15.16-0+deb12u1) ...
Setting up libdeflate0:amd64 (1.14-1) ...
Setting up libapr1:amd64 (1.7.2-3+deb12u1) ...
Setting up libsvtav1enc1:amd64 (1.4.1+dfsg-1) ...
Setting up libjbig0:amd64 (2.1-6.1) ...
Setting up librav1e0:amd64 (0.5.1-6) ...
Setting up libjpeg62-turbo:amd64 (1:2.1.5-2) ...
Setting up ssl-cert (1.1.2) ...
Setting up libevent-2.1-7:amd64 (2.1.12-stable-8) ...
Setting up fonts-dejavu-core (2.37-6) ...
Setting up libgav1-1:amd64 (0.18.0-1+b1) ...
Setting up libsensors5:amd64 (1:3.6.0-7.1) ...
Setting up libdav1d6:amd64 (1.0.0-2+deb12u1) ...
Setting up libltdl7:amd64 (2.4.7-7~deb12u1) ...
Setting up libssh-4:amd64 (0.10.6-0+deb12u2) ...
Setting up libx265-199:amd64 (3.5-2+b1) ...
Setting up libwebp7:amd64 (1.2.4-0.2+deb12u1) ...
Setting up libodbc2:amd64 (2.3.11-2+deb12u1) ...
Setting up fonts-dejavu-extra (2.37-6) ...
Setting up libtiff6:amd64 (4.5.0-6+deb12u3) ...
Setting up liblua5.3-0:amd64 (5.3.6-2) ...
Setting up libxslt1.1:amd64 (1.1.35-1+deb12u3) ...
Setting up apache2-data (2.4.66-1~deb12u1) ...
Setting up zabbix-agent (1:6.0.45-1+debian12) ...
Created symlink /etc/systemd/system/multi-user.target.wants/zabbix-agent.service → /lib/systemd/system/zabbix-agent.service.
Setting up libde265-0:amd64 (1.0.11-1+deb12u2) ...
Setting up libyuv0:amd64 (0.0~git20230123.b2528b0-1) ...
Setting up libopenipmi0 (2.0.33-1+b1) ...
Setting up fping (5.1-1) ...
Setting up libonig5:amd64 (6.9.8-1) ...
Setting up libaprutil1:amd64 (1.6.3-1) ...
Setting up php-common (2:93) ...
Created symlink /etc/systemd/system/timers.target.wants/phpsessionclean.timer → /lib/systemd/system/phpsessionclean.timer.
Setting up fonts-dejavu (2.37-6) ...
Setting up php8.2-common (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/calendar.ini with new version

Creating config file /etc/php/8.2/mods-available/ctype.ini with new version

Creating config file /etc/php/8.2/mods-available/exif.ini with new version

Creating config file /etc/php/8.2/mods-available/fileinfo.ini with new version

Creating config file /etc/php/8.2/mods-available/ffi.ini with new version

Creating config file /etc/php/8.2/mods-available/ftp.ini with new version

Creating config file /etc/php/8.2/mods-available/gettext.ini with new version

Creating config file /etc/php/8.2/mods-available/iconv.ini with new version

Creating config file /etc/php/8.2/mods-available/pdo.ini with new version

Creating config file /etc/php/8.2/mods-available/phar.ini with new version

Creating config file /etc/php/8.2/mods-available/posix.ini with new version

Creating config file /etc/php/8.2/mods-available/shmop.ini with new version

Creating config file /etc/php/8.2/mods-available/sockets.ini with new version

Creating config file /etc/php/8.2/mods-available/sysvmsg.ini with new version

Creating config file /etc/php/8.2/mods-available/sysvsem.ini with new version

Creating config file /etc/php/8.2/mods-available/sysvshm.ini with new version

Creating config file /etc/php/8.2/mods-available/tokenizer.ini with new version
Setting up php8.2-ldap (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/ldap.ini with new version
Setting up php8.2-pgsql (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/pgsql.ini with new version

Creating config file /etc/php/8.2/mods-available/pdo_pgsql.ini with new version
Setting up libavif15:amd64 (0.11.1-1+deb12u1) ...
Setting up php8.2-bcmath (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/bcmath.ini with new version
Setting up fontconfig-config (2.14.1-4) ...
Setting up php8.2-opcache (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/opcache.ini with new version
Setting up php8.2-readline (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/readline.ini with new version
Setting up php8.2-mbstring (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/mbstring.ini with new version
Setting up libheif1:amd64 (1.15.1-1+deb12u1) ...
Setting up libaprutil1-ldap:amd64 (1.6.3-1) ...
Setting up php-mbstring (2:8.2+93) ...
Setting up libaprutil1-dbd-sqlite3:amd64 (1.6.3-1) ...
Setting up php-ldap (2:8.2+93) ...
Setting up libsnmp40:amd64 (5.9.3+dfsg-2+deb12u1) ...
Setting up php8.2-xml (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/dom.ini with new version

Creating config file /etc/php/8.2/mods-available/simplexml.ini with new version

Creating config file /etc/php/8.2/mods-available/xml.ini with new version

Creating config file /etc/php/8.2/mods-available/xmlreader.ini with new version

Creating config file /etc/php/8.2/mods-available/xmlwriter.ini with new version

Creating config file /etc/php/8.2/mods-available/xsl.ini with new version
Setting up zabbix-server-pgsql (1:6.0.45-1+debian12) ...
Setting up libfontconfig1:amd64 (2.14.1-4) ...
Setting up php8.2-cli (8.2.30-1~deb12u1) ...
update-alternatives: using /usr/bin/php8.2 to provide /usr/bin/php (php) in auto mode
update-alternatives: using /usr/bin/phar8.2 to provide /usr/bin/phar (phar) in auto mode
update-alternatives: using /usr/bin/phar.phar8.2 to provide /usr/bin/phar.phar (phar.phar) in auto mode

Creating config file /etc/php/8.2/cli/php.ini with new version
Setting up apache2-utils (2.4.66-1~deb12u1) ...
Setting up php-xml (2:8.2+93) ...
Setting up php-bcmath (2:8.2+93) ...
Setting up snmpd (5.9.3+dfsg-2+deb12u1) ...
adduser: Warning: The home directory `/var/lib/snmp' does not belong to the user you are currently creating.
chown: warning: '.' should be ':': ‘Debian-snmp.Debian-snmp’
Created symlink /etc/systemd/system/multi-user.target.wants/snmpd.service → /lib/systemd/system/snmpd.service.
Setting up apache2-bin (2.4.66-1~deb12u1) ...
Setting up libgd3:amd64 (2.3.3-9) ...
Setting up libapache2-mod-php8.2 (8.2.30-1~deb12u1) ...
Package apache2 is not configured yet. Will defer actions by package libapache2-mod-php8.2.

Creating config file /etc/php/8.2/apache2/php.ini with new version
No module matches 
Setting up libapache2-mod-php (2:8.2+93) ...
Setting up php8.2-gd (8.2.30-1~deb12u1) ...

Creating config file /etc/php/8.2/mods-available/gd.ini with new version
Setting up php-gd (2:8.2+93) ...
Setting up apache2 (2.4.66-1~deb12u1) ...
Enabling module mpm_event.
Enabling module authz_core.
Enabling module authz_host.
Enabling module authn_core.
Enabling module auth_basic.
Enabling module access_compat.
Enabling module authn_file.
Enabling module authz_user.
Enabling module alias.
Enabling module dir.
Enabling module autoindex.
Enabling module env.
Enabling module mime.
Enabling module negotiation.
Enabling module setenvif.
Enabling module filter.
Enabling module deflate.
Enabling module status.
Enabling module reqtimeout.
Enabling conf charset.
Enabling conf localized-error-pages.
Enabling conf other-vhosts-access-log.
Enabling conf security.
Enabling conf serve-cgi-bin.
Enabling site 000-default.
info: Switch to mpm prefork for package libapache2-mod-php8.2
Module mpm_event disabled.
Enabling module mpm_prefork.
info: Executing deferred 'a2enmod php8.2' for package libapache2-mod-php8.2
Enabling module php8.2.
Created symlink /etc/systemd/system/multi-user.target.wants/apache2.service → /lib/systemd/system/apache2.service.
Created symlink /etc/systemd/system/multi-user.target.wants/apache-htcacheclean.service → /lib/systemd/system/apache-htcacheclean.service.
Setting up zabbix-frontend-php (1:6.0.45-1+debian12) ...
update-alternatives: using /usr/share/fonts/truetype/dejavu/DejaVuSans.ttf to provide /usr/share/zabbix/assets/fonts/graphfont.ttf (zabbix-frontend-font) in auto mode
Setting up zabbix-apache-conf (1:6.0.45-1+debian12) ...
Enabling conf zabbix.
To activate the new configuration, you need to run:
  systemctl reload apache2
Processing triggers for libc-bin (2.36-9+deb12u13) ...
Processing triggers for php8.2-cli (8.2.30-1~deb12u1) ...
Processing triggers for libapache2-mod-php8.2 (8.2.30-1~deb12u1) ...
student1@myvm:~$ sudo apt install postqresql
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
E: Unable to locate package postqresql
student1@myvm:~$ sudo apt install postgresql
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libcommon-sense-perl libjson-perl libjson-xs-perl libllvm14 libtypes-serialiser-perl
  libz3-4 postgresql-15 postgresql-client-15 postgresql-client-common
  postgresql-common sysstat
Suggested packages:
  postgresql-doc postgresql-doc-15 isag
The following NEW packages will be installed:
  libcommon-sense-perl libjson-perl libjson-xs-perl libllvm14 libtypes-serialiser-perl
  libz3-4 postgresql postgresql-15 postgresql-client-15 postgresql-client-common
  postgresql-common sysstat
0 upgraded, 12 newly installed, 0 to remove and 5 not upgraded.
Need to get 48.7 MB of archives.
After this operation, 199 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://mirror.yandex.ru/debian bookworm/main amd64 libjson-perl all 4.10000-1 [87.5 kB]
Get:2 http://mirror.yandex.ru/debian bookworm/main amd64 postgresql-client-common all 248+deb12u1 [35.2 kB]
Get:3 http://mirror.yandex.ru/debian bookworm/main amd64 postgresql-common all 248+deb12u1 [179 kB]
Get:4 http://mirror.yandex.ru/debian bookworm/main amd64 libcommon-sense-perl amd64 3.75-3 [23.0 kB]
Get:5 http://security.debian.org bookworm-security/main amd64 postgresql-client-15 amd64 15.16-0+deb12u1 [1,741 kB]
Get:6 http://mirror.yandex.ru/debian bookworm/main amd64 libtypes-serialiser-perl all 1.01-1 [12.2 kB]
Get:7 http://mirror.yandex.ru/debian bookworm/main amd64 libjson-xs-perl amd64 4.040-1~deb12u1 [92.4 kB]
Get:8 http://mirror.yandex.ru/debian bookworm/main amd64 libz3-4 amd64 4.8.12-3.1 [7,216 kB]
Get:9 http://mirror.yandex.ru/debian bookworm/main amd64 libllvm14 amd64 1:14.0.6-12 [21.8 MB]
Get:10 http://security.debian.org bookworm-security/main amd64 postgresql-15 amd64 15.16-0+deb12u1 [16.9 MB]
Get:11 http://mirror.yandex.ru/debian bookworm/main amd64 postgresql all 15+248+deb12u1 [10.2 kB]
Get:12 http://mirror.yandex.ru/debian bookworm/main amd64 sysstat amd64 12.6.1-1 [596 kB]
Fetched 48.7 MB in 1s (56.2 MB/s)  
Preconfiguring packages ...
Selecting previously unselected package libjson-perl.
(Reading database ... 38629 files and directories currently installed.)
Preparing to unpack .../00-libjson-perl_4.10000-1_all.deb ...
Unpacking libjson-perl (4.10000-1) ...
Selecting previously unselected package postgresql-client-common.
Preparing to unpack .../01-postgresql-client-common_248+deb12u1_all.deb ...
Unpacking postgresql-client-common (248+deb12u1) ...
Selecting previously unselected package postgresql-common.
Preparing to unpack .../02-postgresql-common_248+deb12u1_all.deb ...
Adding 'diversion of /usr/bin/pg_config to /usr/bin/pg_config.libpq-dev by postgresql-common'
Unpacking postgresql-common (248+deb12u1) ...
Selecting previously unselected package libcommon-sense-perl:amd64.
Preparing to unpack .../03-libcommon-sense-perl_3.75-3_amd64.deb ...
Unpacking libcommon-sense-perl:amd64 (3.75-3) ...
Selecting previously unselected package libtypes-serialiser-perl.
Preparing to unpack .../04-libtypes-serialiser-perl_1.01-1_all.deb ...
Unpacking libtypes-serialiser-perl (1.01-1) ...
Selecting previously unselected package libjson-xs-perl.
Preparing to unpack .../05-libjson-xs-perl_4.040-1~deb12u1_amd64.deb ...
Unpacking libjson-xs-perl (4.040-1~deb12u1) ...
Selecting previously unselected package libz3-4:amd64.
Preparing to unpack .../06-libz3-4_4.8.12-3.1_amd64.deb ...
Unpacking libz3-4:amd64 (4.8.12-3.1) ...
Selecting previously unselected package libllvm14:amd64.
Preparing to unpack .../07-libllvm14_1%3a14.0.6-12_amd64.deb ...
Unpacking libllvm14:amd64 (1:14.0.6-12) ...
Selecting previously unselected package postgresql-client-15.
Preparing to unpack .../08-postgresql-client-15_15.16-0+deb12u1_amd64.deb ...
Unpacking postgresql-client-15 (15.16-0+deb12u1) ...
Selecting previously unselected package postgresql-15.
Preparing to unpack .../09-postgresql-15_15.16-0+deb12u1_amd64.deb ...
Unpacking postgresql-15 (15.16-0+deb12u1) ...
Selecting previously unselected package postgresql.
Preparing to unpack .../10-postgresql_15+248+deb12u1_all.deb ...
Unpacking postgresql (15+248+deb12u1) ...
Selecting previously unselected package sysstat.
Preparing to unpack .../11-sysstat_12.6.1-1_amd64.deb ...
Unpacking sysstat (12.6.1-1) ...
Setting up postgresql-client-common (248+deb12u1) ...
Setting up libcommon-sense-perl:amd64 (3.75-3) ...
Setting up postgresql-client-15 (15.16-0+deb12u1) ...
update-alternatives: using /usr/share/postgresql/15/man/man1/psql.1.gz to provide /usr/share/man/man1/psql.1.gz (psql.1.gz) in auto mode
Setting up libz3-4:amd64 (4.8.12-3.1) ...
Setting up libllvm14:amd64 (1:14.0.6-12) ...
Setting up libtypes-serialiser-perl (1.01-1) ...
Setting up libjson-perl (4.10000-1) ...
Setting up sysstat (12.6.1-1) ...

Creating config file /etc/default/sysstat with new version
update-alternatives: using /usr/bin/sar.sysstat to provide /usr/bin/sar (sar) in auto mode
Created symlink /etc/systemd/system/sysstat.service.wants/sysstat-collect.timer → /lib/systemd/system/sysstat-collect.timer.
Created symlink /etc/systemd/system/sysstat.service.wants/sysstat-summary.timer → /lib/systemd/system/sysstat-summary.timer.
Created symlink /etc/systemd/system/multi-user.target.wants/sysstat.service → /lib/systemd/system/sysstat.service.
Setting up libjson-xs-perl (4.040-1~deb12u1) ...
Setting up postgresql-common (248+deb12u1) ...

Creating config file /etc/postgresql-common/createcluster.conf with new version
Building PostgreSQL dictionaries from installed myspell/hunspell packages...
Removing obsolete dictionary files:
Created symlink /etc/systemd/system/multi-user.target.wants/postgresql.service → /lib/systemd/system/postgresql.service.
Setting up postgresql-15 (15.16-0+deb12u1) ...
Creating new PostgreSQL cluster 15/main ...
/usr/lib/postgresql/15/bin/initdb -D /var/lib/postgresql/15/main --auth-local peer --auth-host scram-sha-256 --no-instructions
The files belonging to this database system will be owned by user "postgres".
This user must also own the server process.

The database cluster will be initialized with locale "en_US.UTF-8".
The default database encoding has accordingly been set to "UTF8".
The default text search configuration will be set to "english".

Data page checksums are disabled.

fixing permissions on existing directory /var/lib/postgresql/15/main ... ok
creating subdirectories ... ok
selecting dynamic shared memory implementation ... posix
selecting default max_connections ... 100
selecting default shared_buffers ... 128MB
selecting default time zone ... Etc/UTC
creating configuration files ... ok
running bootstrap script ... ok
performing post-bootstrap initialization ... ok
syncing data to disk ... ok
update-alternatives: using /usr/share/postgresql/15/man/man1/postmaster.1.gz to provide /usr/share/man/man1/postmaster.1.gz (postmaster.1.gz) in auto mode
Setting up postgresql (15+248+deb12u1) ...
Processing triggers for libc-bin (2.36-9+deb12u13) ...
student1@myvm:~$ sudo apt install zabbix-server-pgsql zabbix-frontend-php php7.4-pgsql zabbix-apache-conf zabbix-sql-
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
E: Unable to locate package php7.4-pgsql
E: Couldn't find any package by glob 'php7.4-pgsql'
E: Unable to locate package zabbix-sql
student1@myvm:~$ sudo apt install zabbix-server-pgsql zabbix-frontend-php php7.4-pgsql zabbix-apache-conf zabbix-sql-scripts nano -y # zabbix-agent
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
E: Unable to locate package php7.4-pgsql
E: Couldn't find any package by glob 'php7.4-pgsql'
student1@myvm:~$ sudo apt install zabbix-server-pgsql zabbix-frontend-php php7.4-pgsql zabbix-apache-conf zabbix-sql- scripts nano -y # zabbix-agent
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
E: Unable to locate package php7.4-pgsql
E: Couldn't find any package by glob 'php7.4-pgsql'
E: Unable to locate package zabbix-sql
E: Unable to locate package scripts
student1@myvm:~$ sudo -u postgres createuser --pwprompt zabbix
Enter password for new role: 
Enter it again: 
student1@myvm:~$ sudo -u postgres createdb -O zabbix zabbix
student1@myvm:~$ zcat /usr/share/zabbix-sql-scripts/postgresql/server.sql.gz | sudo -u zabbix psql zabbix
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE TABLE
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
CREATE INDEX
CREATE TABLE
INSERT 0 1
CREATE FUNCTION
CREATE TRIGGER
CREATE TRIGGER
CREATE FUNCTION
CREATE TRIGGER
CREATE TRIGGER
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
ALTER TABLE
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
START TRANSACTION
INSERT 0 4
INSERT 0 2
INSERT 0 18
INSERT 0 1
INSERT 0 1
INSERT 0 36
INSERT 0 633
INSERT 0 188
INSERT 0 5
INSERT 0 3
INSERT 0 3
INSERT 0 5
INSERT 0 10
INSERT 0 8
INSERT 0 4
INSERT 0 1
INSERT 0 6
INSERT 0 1
INSERT 0 4
INSERT 0 1
INSERT 0 5
INSERT 0 10
INSERT 0 1
INSERT 0 27
INSERT 0 431
INSERT 0 67
INSERT 0 26
INSERT 0 1296
INSERT 0 9596
INSERT 0 4645
INSERT 0 1656
INSERT 0 437
INSERT 0 116
INSERT 0 10
INSERT 0 4
INSERT 0 1
INSERT 0 6428
INSERT 0 66
INSERT 0 1874
INSERT 0 10323
INSERT 0 1997
INSERT 0 29
INSERT 0 5350
INSERT 0 6178
INSERT 0 390
INSERT 0 42
INSERT 0 34070
INSERT 0 1
INSERT 0 1
INSERT 0 7040
INSERT 0 46
INSERT 0 2971
INSERT 0 103
INSERT 0 8327
INSERT 0 17842
INSERT 0 1
INSERT 0 832
INSERT 0 1022
INSERT 0 148
INSERT 0 145
INSERT 0 161
INSERT 0 16
INSERT 0 147
INSERT 0 3
INSERT 0 14
INSERT 0 1301
INSERT 0 25801
INSERT 0 343
INSERT 0 1
INSERT 0 500
INSERT 0 1965
INSERT 0 5861
COMMIT
student1@myvm:~$ sudo nano /etc/zabbix/zabbix_server.conf
student1@myvm:~$ systemctl restart zabbix-server zabbix-agent apache2
Failed to execute /usr/bin/pkttyagent: No such file or directory
Failed to restart zabbix-server.service: Access denied
See system logs and 'systemctl status zabbix-server.service' for details.
Failed to restart zabbix-agent.service: Access denied
See system logs and 'systemctl status zabbix-agent.service' for details.
Failed to restart apache2.service: Access denied
See system logs and 'systemctl status apache2.service' for details.
student1@myvm:~$ sudo su
root@myvm:/home/student1# systemctl restart zabbix-server zabbix-agent apache2
root@myvm:/home/student1# systemctl enable zabbix-server zabbix-agent apache2
Synchronizing state of zabbix-server.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable zabbix-server
Synchronizing state of zabbix-agent.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable zabbix-agent
Synchronizing state of apache2.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable apache2
Created symlink /etc/systemd/system/multi-user.target.wants/zabbix-server.service → /lib/systemd/system/zabbix-server.service.
root@myvm:/home/student1# nano /etc/zabbix/zabbix_server.conf
root@myvm:/home/student1# systemctl restart zabbix-server zabbix-agent apache2
root@myvm:/home/student1# nano /etc/zabbix/zabbix_server.conf
root@myvm:/home/student1# cat /var/log/zabbix/zabbix_agentd.log
  3416:20260402:091306.967 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
  3416:20260402:091306.967 **** Enabled features ****
  3416:20260402:091306.967 IPv6 support:          YES
  3416:20260402:091306.967 TLS support:           YES
  3416:20260402:091306.967 **************************
  3416:20260402:091306.967 using configuration file: /etc/zabbix/zabbix_agentd.conf
  3416:20260402:091306.968 agent #0 started [main process]
  3417:20260402:091306.968 agent #1 started [collector]
  3419:20260402:091306.969 agent #3 started [listener #2]
  3420:20260402:091306.969 agent #4 started [listener #3]
  3421:20260402:091306.971 agent #5 started [active checks #1]
  3418:20260402:091306.971 agent #2 started [listener #1]
  3421:20260402:091306.973 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
  3421:20260402:091306.973 Active check configuration update started to fail
  3416:20260402:094441.004 Got signal [signal:15(SIGTERM),sender_pid:15714,sender_uid:104,reason:0]. Exiting ...
  3416:20260402:094441.011 Zabbix Agent stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 15722:20260402:094441.075 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
 15722:20260402:094441.075 **** Enabled features ****
 15722:20260402:094441.075 IPv6 support:          YES
 15722:20260402:094441.075 TLS support:           YES
 15722:20260402:094441.075 **************************
 15722:20260402:094441.075 using configuration file: /etc/zabbix/zabbix_agentd.conf
 15722:20260402:094441.075 agent #0 started [main process]
 15723:20260402:094441.076 agent #1 started [collector]
 15724:20260402:094441.076 agent #2 started [listener #1]
 15727:20260402:094441.077 agent #5 started [active checks #1]
 15727:20260402:094441.080 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
 15727:20260402:094441.080 Active check configuration update started to fail
 15726:20260402:094441.080 agent #4 started [listener #3]
 15725:20260402:094441.080 agent #3 started [listener #2]
 15722:20260402:095247.523 Got signal [signal:15(SIGTERM),sender_pid:16092,sender_uid:104,reason:0]. Exiting ...
 15722:20260402:095247.525 Zabbix Agent stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 16101:20260402:095247.579 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
 16101:20260402:095247.580 **** Enabled features ****
 16101:20260402:095247.580 IPv6 support:          YES
 16101:20260402:095247.580 TLS support:           YES
 16101:20260402:095247.580 **************************
 16101:20260402:095247.580 using configuration file: /etc/zabbix/zabbix_agentd.conf
 16101:20260402:095247.580 agent #0 started [main process]
 16102:20260402:095247.580 agent #1 started [collector]
 16104:20260402:095247.580 agent #2 started [listener #1]
 16105:20260402:095247.583 agent #3 started [listener #2]
 16106:20260402:095247.583 agent #4 started [listener #3]
 16107:20260402:095247.584 agent #5 started [active checks #1]
 16107:20260402:095247.586 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
 16107:20260402:095247.586 Active check configuration update started to fail
 16107:20260402:095347.595 Active check configuration update from [127.0.0.1:10051] is working again
 16106:20260402:100550.669 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16106:20260402:100605.628 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16104:20260402:100620.644 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16105:20260402:100635.659 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
root@myvm:/home/student1#           
sudo nano /etc/zabbix/zabbix_agentd.conf
root@myvm:/home/student1# sudo systemctl restart zabbix-agent
root@myvm:/home/student1# cat /var/log/zabbix/zabbix_agentd.log
  3416:20260402:091306.967 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
  3416:20260402:091306.967 **** Enabled features ****
  3416:20260402:091306.967 IPv6 support:          YES
  3416:20260402:091306.967 TLS support:           YES
  3416:20260402:091306.967 **************************
  3416:20260402:091306.967 using configuration file: /etc/zabbix/zabbix_agentd.conf
  3416:20260402:091306.968 agent #0 started [main process]
  3417:20260402:091306.968 agent #1 started [collector]
  3419:20260402:091306.969 agent #3 started [listener #2]
  3420:20260402:091306.969 agent #4 started [listener #3]
  3421:20260402:091306.971 agent #5 started [active checks #1]
  3418:20260402:091306.971 agent #2 started [listener #1]
  3421:20260402:091306.973 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
  3421:20260402:091306.973 Active check configuration update started to fail
  3416:20260402:094441.004 Got signal [signal:15(SIGTERM),sender_pid:15714,sender_uid:104,reason:0]. Exiting ...
  3416:20260402:094441.011 Zabbix Agent stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 15722:20260402:094441.075 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
 15722:20260402:094441.075 **** Enabled features ****
 15722:20260402:094441.075 IPv6 support:          YES
 15722:20260402:094441.075 TLS support:           YES
 15722:20260402:094441.075 **************************
 15722:20260402:094441.075 using configuration file: /etc/zabbix/zabbix_agentd.conf
 15722:20260402:094441.075 agent #0 started [main process]
 15723:20260402:094441.076 agent #1 started [collector]
 15724:20260402:094441.076 agent #2 started [listener #1]
 15727:20260402:094441.077 agent #5 started [active checks #1]
 15727:20260402:094441.080 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
 15727:20260402:094441.080 Active check configuration update started to fail
 15726:20260402:094441.080 agent #4 started [listener #3]
 15725:20260402:094441.080 agent #3 started [listener #2]
 15722:20260402:095247.523 Got signal [signal:15(SIGTERM),sender_pid:16092,sender_uid:104,reason:0]. Exiting ...
 15722:20260402:095247.525 Zabbix Agent stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 16101:20260402:095247.579 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
 16101:20260402:095247.580 **** Enabled features ****
 16101:20260402:095247.580 IPv6 support:          YES
 16101:20260402:095247.580 TLS support:           YES
 16101:20260402:095247.580 **************************
 16101:20260402:095247.580 using configuration file: /etc/zabbix/zabbix_agentd.conf
 16101:20260402:095247.580 agent #0 started [main process]
 16102:20260402:095247.580 agent #1 started [collector]
 16104:20260402:095247.580 agent #2 started [listener #1]
 16105:20260402:095247.583 agent #3 started [listener #2]
 16106:20260402:095247.583 agent #4 started [listener #3]
 16107:20260402:095247.584 agent #5 started [active checks #1]
 16107:20260402:095247.586 Unable to connect to [127.0.0.1]:10051 [cannot connect to [[127.0.0.1]:10051]: [111] Connection refused]
 16107:20260402:095247.586 Active check configuration update started to fail
 16107:20260402:095347.595 Active check configuration update from [127.0.0.1:10051] is working again
 16106:20260402:100550.669 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16106:20260402:100605.628 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16104:20260402:100620.644 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16105:20260402:100635.659 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16105:20260402:100735.714 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16106:20260402:100835.764 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16104:20260402:100935.817 failed to accept an incoming connection: connection from "213.165.215.56" rejected, allowed hosts: "127.0.0.1"
 16101:20260402:101031.108 Got signal [signal:15(SIGTERM),sender_pid:16668,sender_uid:104,reason:0]. Exiting ...
 16101:20260402:101031.112 Zabbix Agent stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 16673:20260402:101031.170 Starting Zabbix Agent [Zabbix server]. Zabbix 6.0.45 (revision d8c5768f7d0).
 16673:20260402:101031.170 **** Enabled features ****
 16673:20260402:101031.170 IPv6 support:          YES
 16673:20260402:101031.170 TLS support:           YES
 16673:20260402:101031.170 **************************
 16673:20260402:101031.170 using configuration file: /etc/zabbix/zabbix_agentd.conf
 16673:20260402:101031.170 agent #0 started [main process]
 16674:20260402:101031.171 agent #1 started [collector]
 16675:20260402:101031.171 agent #2 started [listener #1]
 16678:20260402:101031.172 agent #5 started [active checks #1]
 16677:20260402:101031.173 agent #4 started [listener #3]
 16676:20260402:101031.173 agent #3 started [listener #2]
 16677:20260402:101048.974 failed to accept an incoming connection: connection from "127.0.0.1" rejected, allowed hosts: "213.165.215.56"
root@myvm:/home/student1# 
root@myvm:/home/student1# restart zabbix-server 
bash: restart: command not found
root@myvm:/home/student1# sudo restart zabbix-server 
sudo: restart: command not found
root@myvm:/home/student1# sudo systemctl restart zabbix-server
root@myvm:/home/student1# sudo systemctl restart zabbix-server apache2
root@myvm:/home/student1# sudo systemctl enable zabbix-server apache2
Synchronizing state of zabbix-server.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable zabbix-server
Synchronizing state of apache2.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable apache2
root@myvm:/home/student1# sudo systemctl enable zabbix-server apache2
Synchronizing state of zabbix-server.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable zabbix-server
Synchronizing state of apache2.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable apache2
root@myvm:/home/student1# /var/log/zabbix/
bash: /var/log/zabbix/: Is a directory
root@myvm:/home/student1# sudo nano /var/log/zabbix/
root@myvm:/home/student1# cat /var/log/zabbix/
cat: /var/log/zabbix/: Is a directory
root@myvm:/home/student1# cat /var/log/zabbix/zabbix_server.log
 15729:20260402:094441.113 Starting Zabbix Server. Zabbix 6.0.45 (revision d8c5768f7d0).
 15729:20260402:094441.113 ****** Enabled features ******
 15729:20260402:094441.113 SNMP monitoring:           YES
 15729:20260402:094441.113 IPMI monitoring:           YES
 15729:20260402:094441.113 Web monitoring:            YES
 15729:20260402:094441.113 VMware monitoring:         YES
 15729:20260402:094441.113 SMTP authentication:       YES
 15729:20260402:094441.113 ODBC:                      YES
 15729:20260402:094441.113 SSH support:               YES
 15729:20260402:094441.113 IPv6 support:              YES
 15729:20260402:094441.113 TLS support:               YES
 15729:20260402:094441.113 ******************************
 15729:20260402:094441.113 using configuration file: /etc/zabbix/zabbix_server.conf
 15729:20260402:094441.150 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094441.150 database is down: reconnecting in 10 seconds
 15729:20260402:094451.171 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094451.171 database is down: reconnecting in 10 seconds
 15729:20260402:094501.193 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094501.193 database is down: reconnecting in 10 seconds
 15729:20260402:094511.213 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094511.213 database is down: reconnecting in 10 seconds
 15729:20260402:094521.232 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094521.232 database is down: reconnecting in 10 seconds
 15729:20260402:094531.255 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094531.255 database is down: reconnecting in 10 seconds
 15729:20260402:094541.275 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094541.275 database is down: reconnecting in 10 seconds
 15729:20260402:094551.294 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094551.294 database is down: reconnecting in 10 seconds
 15729:20260402:094601.313 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094601.313 database is down: reconnecting in 10 seconds
 15729:20260402:094611.332 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094611.332 database is down: reconnecting in 10 seconds
 15729:20260402:094621.353 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094621.353 database is down: reconnecting in 10 seconds
 15729:20260402:094631.373 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094631.373 database is down: reconnecting in 10 seconds
 15729:20260402:094641.392 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094641.392 database is down: reconnecting in 10 seconds
 15729:20260402:094651.412 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094651.412 database is down: reconnecting in 10 seconds
 15729:20260402:094701.435 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094701.435 database is down: reconnecting in 10 seconds
 15729:20260402:094711.453 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094711.453 database is down: reconnecting in 10 seconds
 15729:20260402:094721.471 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094721.471 database is down: reconnecting in 10 seconds
 15729:20260402:094731.489 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094731.489 database is down: reconnecting in 10 seconds
 15729:20260402:094741.506 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094741.506 database is down: reconnecting in 10 seconds
 15729:20260402:094751.523 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094751.523 database is down: reconnecting in 10 seconds
 15729:20260402:094801.540 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094801.541 database is down: reconnecting in 10 seconds
 15729:20260402:094811.558 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094811.558 database is down: reconnecting in 10 seconds
 15729:20260402:094821.575 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094821.575 database is down: reconnecting in 10 seconds
 15729:20260402:094831.594 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094831.594 database is down: reconnecting in 10 seconds
 15729:20260402:094841.616 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094841.616 database is down: reconnecting in 10 seconds
 15729:20260402:094851.636 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094851.636 database is down: reconnecting in 10 seconds
 15729:20260402:094901.657 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094901.657 database is down: reconnecting in 10 seconds
 15729:20260402:094911.677 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094911.677 database is down: reconnecting in 10 seconds
 15729:20260402:094921.696 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094921.696 database is down: reconnecting in 10 seconds
 15729:20260402:094931.716 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094931.716 database is down: reconnecting in 10 seconds
 15729:20260402:094941.740 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094941.740 database is down: reconnecting in 10 seconds
 15729:20260402:094951.760 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:094951.760 database is down: reconnecting in 10 seconds
 15729:20260402:095001.785 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095001.785 database is down: reconnecting in 10 seconds
 15729:20260402:095011.807 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095011.807 database is down: reconnecting in 10 seconds
 15729:20260402:095021.825 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095021.825 database is down: reconnecting in 10 seconds
 15729:20260402:095031.845 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095031.845 database is down: reconnecting in 10 seconds
 15729:20260402:095041.865 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095041.865 database is down: reconnecting in 10 seconds
 15729:20260402:095051.885 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095051.885 database is down: reconnecting in 10 seconds
 15729:20260402:095101.904 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095101.904 database is down: reconnecting in 10 seconds
 15729:20260402:095111.924 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095111.924 database is down: reconnecting in 10 seconds
 15729:20260402:095121.943 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095121.943 database is down: reconnecting in 10 seconds
 15729:20260402:095131.964 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095131.964 database is down: reconnecting in 10 seconds
 15729:20260402:095141.984 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095141.984 database is down: reconnecting in 10 seconds
 15729:20260402:095152.003 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095152.003 database is down: reconnecting in 10 seconds
 15729:20260402:095202.023 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095202.023 database is down: reconnecting in 10 seconds
 15729:20260402:095212.043 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095212.043 database is down: reconnecting in 10 seconds
 15729:20260402:095222.062 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095222.062 database is down: reconnecting in 10 seconds
 15729:20260402:095232.083 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095232.083 database is down: reconnecting in 10 seconds
 15729:20260402:095242.103 [Z3001] connection to database 'zabbix' failed: [0] connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"
connection to server at "localhost" (::1), port 5432 failed: FATAL:  password authentication failed for user "zabbix"

 15729:20260402:095242.103 database is down: reconnecting in 10 seconds
 15729:20260402:095247.517 Got signal [signal:15(SIGTERM),sender_pid:16091,sender_uid:0,reason:0]. Exiting ...
 15729:20260402:095247.517 Zabbix Server stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 16108:20260402:095247.583 Starting Zabbix Server. Zabbix 6.0.45 (revision d8c5768f7d0).
 16108:20260402:095247.583 ****** Enabled features ******
 16108:20260402:095247.583 SNMP monitoring:           YES
 16108:20260402:095247.583 IPMI monitoring:           YES
 16108:20260402:095247.583 Web monitoring:            YES
 16108:20260402:095247.583 VMware monitoring:         YES
 16108:20260402:095247.583 SMTP authentication:       YES
 16108:20260402:095247.583 ODBC:                      YES
 16108:20260402:095247.583 SSH support:               YES
 16108:20260402:095247.583 IPv6 support:              YES
 16108:20260402:095247.583 TLS support:               YES
 16108:20260402:095247.583 ******************************
 16108:20260402:095247.583 using configuration file: /etc/zabbix/zabbix_server.conf
 16108:20260402:095247.625 current database version (mandatory/optional): 06000000/06000055
 16108:20260402:095247.625 required mandatory version: 06000000
 16117:20260402:095247.643 starting HA manager
 16117:20260402:095247.668 HA manager started in active mode
 16108:20260402:095247.671 server #0 started [main process]
 16121:20260402:095247.672 server #2 started [configuration syncer #1]
 16120:20260402:095247.675 server #1 started [service manager #1]
 16132:20260402:095247.830 server #5 started [alerter #2]
 16133:20260402:095247.830 server #6 started [alerter #3]
 16134:20260402:095247.830 server #7 started [preprocessing manager #1]
 16135:20260402:095247.831 server #8 started [preprocessing worker #1]
 16136:20260402:095247.831 server #9 started [preprocessing worker #2]
 16137:20260402:095247.831 server #10 started [preprocessing worker #3]
 16130:20260402:095247.832 server #3 started [alert manager #1]
 16145:20260402:095247.834 server #17 started [discoverer #1]
 16138:20260402:095247.834 server #11 started [lld manager #1]
 16139:20260402:095247.834 server #12 started [lld worker #1]
 16131:20260402:095247.835 server #4 started [alerter #1]
 16147:20260402:095247.836 server #19 started [history syncer #2]
 16144:20260402:095247.836 server #16 started [http poller #1]
 16154:20260402:095247.838 server #23 started [proxy poller #1]
 16146:20260402:095247.839 server #18 started [history syncer #1]
 16148:20260402:095247.840 server #20 started [history syncer #3]
 16140:20260402:095247.840 server #13 started [lld worker #2]
 16151:20260402:095247.841 server #21 started [history syncer #4]
 16153:20260402:095247.841 server #22 started [escalator #1]
 16142:20260402:095247.842 server #15 started [timer #1]
 16141:20260402:095247.843 server #14 started [housekeeper #1]
 16156:20260402:095247.843 server #24 started [self-monitoring #1]
 16157:20260402:095247.847 server #25 started [task manager #1]
 16158:20260402:095247.848 server #26 started [poller #1]
 16159:20260402:095247.849 server #27 started [poller #2]
 16169:20260402:095247.863 server #29 started [poller #4]
 16170:20260402:095247.864 server #30 started [poller #5]
 16168:20260402:095247.865 server #28 started [poller #3]
 16171:20260402:095247.867 server #31 started [unreachable poller #1]
 16172:20260402:095247.869 server #32 started [trapper #1]
 16177:20260402:095247.893 server #35 started [trapper #4]
 16176:20260402:095247.894 server #34 started [trapper #3]
 16178:20260402:095247.899 server #36 started [trapper #5]
 16175:20260402:095247.901 server #33 started [trapper #2]
 16179:20260402:095247.904 server #37 started [icmp pinger #1]
 16180:20260402:095247.908 server #38 started [alert syncer #1]
 16181:20260402:095247.941 server #39 started [history poller #1]
 16182:20260402:095247.955 server #40 started [history poller #2]
 16189:20260402:095247.973 server #41 started [history poller #3]
 16194:20260402:095247.980 server #45 started [trigger housekeeper #1]
 16192:20260402:095247.988 server #43 started [history poller #5]
 16193:20260402:095247.993 server #44 started [availability manager #1]
 16191:20260402:095248.004 server #42 started [history poller #4]
 16199:20260402:095248.010 server #46 started [odbc poller #1]
 16159:20260402:095248.851 enabling Zabbix agent checks on host "Zabbix server": interface became available
 16147:20260402:095248.901 item "Zabbix server:zabbix[process,vmware collector,avg,busy]" became not supported: No "vmware collector" processes started.
 16147:20260402:095255.942 item "Zabbix server:zabbix[vmware,buffer,pused]" became not supported: No "vmware collector" processes started.
 16148:20260402:095258.963 item "Zabbix server:zabbix[process,report writer,avg,busy]" became not supported: No "report writer" processes started.
 16147:20260402:095259.964 item "Zabbix server:zabbix[process,report manager,avg,busy]" became not supported: No "report manager" processes started.
 16147:20260402:095342.004 item "Zabbix server:zabbix[process,ipmi poller,avg,busy]" became not supported: No "ipmi poller" processes started.
 16151:20260402:095343.005 item "Zabbix server:zabbix[process,java poller,avg,busy]" became not supported: No "java poller" processes started.
 16151:20260402:095348.010 item "Zabbix server:zabbix[process,snmp trapper,avg,busy]" became not supported: No "snmp trapper" processes started.
 16151:20260402:095348.010 item "Zabbix server:zabbix[process,ipmi manager,avg,busy]" became not supported: No "ipmi manager" processes started.
 16169:20260402:100550.669 Zabbix agent item "vm.memory.size[available]" on host "test" failed: first network error, wait for 15 seconds
 16171:20260402:100605.628 Zabbix agent item "vm.memory.size[pavailable]" on host "test" failed: another network error, wait for 15 seconds
 16171:20260402:100620.644 Zabbix agent item "system.cpu.load[all,avg1]" on host "test" failed: another network error, wait for 15 seconds
 16171:20260402:100635.659 temporarily disabling Zabbix agent checks on host "test": interface unavailable
 16171:20260402:101035.877 enabling Zabbix agent checks on host "test": interface became available
 16168:20260402:101048.974 Zabbix agent item "system.swap.size[,free]" on host "Zabbix server" failed: first network error, wait for 15 seconds
 16171:20260402:101103.907 Zabbix agent item "system.cpu.util[,system]" on host "Zabbix server" failed: another network error, wait for 15 seconds
 16171:20260402:101118.923 Zabbix agent item "system.swap.size[,total]" on host "Zabbix server" failed: another network error, wait for 15 seconds
 16171:20260402:101133.939 temporarily disabling Zabbix agent checks on host "Zabbix server": interface unavailable
 16146:20260402:102051.608 item "test:vfs.dev.read.await[vda]" became not supported: Cannot evaluate function: not enough data at "last(//vfs.dev.read.time.rate[vda])/(last(//vfs.dev.read.rate[vda])+(last(//vfs.dev.read.rate[vda])=0)))*1000*(last(//vfs.dev.read.rate[vda]) > 0)".
 16147:20260402:102052.608 item "test:vfs.dev.write.await[vda]" became not supported: Cannot evaluate function: not enough data at "last(//vfs.dev.write.time.rate[vda])/(last(//vfs.dev.write.rate[vda])+(last(//vfs.dev.write.rate[vda])=0)))*1000*(last(//vfs.dev.write.rate[vda]) > 0)".
 16148:20260402:102151.653 item "test:vfs.dev.read.await[vda]" became supported
 16151:20260402:102152.654 item "test:vfs.dev.write.await[vda]" became supported
 16141:20260402:102248.043 executing housekeeper
 16141:20260402:102248.088 housekeeper [deleted 0 hist/trends, 0 items/triggers, 0 events, 0 problems, 0 sessions, 0 alarms, 0 audit, 0 autoreg_host, 0 records in 0.031065 sec, idle for 1 hour(s)]
 16146:20260402:102450.795 item "test:vfs.file.contents["/sys/class/net/eth0/speed"]" became not supported: Value "-1000000" of type "double" is not suitable for value type "Numeric (unsigned)"
 16158:20260402:103204.408 Zabbix agent item "system.uptime" on host "test 2" failed: first network error, wait for 15 seconds
 16171:20260402:103219.146 Zabbix agent item "system.users.num" on host "test 2" failed: another network error, wait for 15 seconds
 16171:20260402:103234.163 enabling Zabbix agent checks on host "test 2": interface became available
 16108:20260402:103629.605 Got signal [signal:15(SIGTERM),sender_pid:17253,sender_uid:0,reason:0]. Exiting ...
 16117:20260402:103629.647 HA manager has been paused
 16148:20260402:103629.648 syncing history data in progress... 
 16148:20260402:103629.648 syncing history data done
 16117:20260402:103630.968 HA manager has been stopped
 16108:20260402:103630.984 syncing trend data...
 16108:20260402:103631.003 syncing trend data done
 16108:20260402:103631.004 Zabbix Server stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 17259:20260402:103631.114 Starting Zabbix Server. Zabbix 6.0.45 (revision d8c5768f7d0).
 17259:20260402:103631.114 ****** Enabled features ******
 17259:20260402:103631.114 SNMP monitoring:           YES
 17259:20260402:103631.114 IPMI monitoring:           YES
 17259:20260402:103631.114 Web monitoring:            YES
 17259:20260402:103631.114 VMware monitoring:         YES
 17259:20260402:103631.114 SMTP authentication:       YES
 17259:20260402:103631.114 ODBC:                      YES
 17259:20260402:103631.114 SSH support:               YES
 17259:20260402:103631.114 IPv6 support:              YES
 17259:20260402:103631.114 TLS support:               YES
 17259:20260402:103631.114 ******************************
 17259:20260402:103631.114 using configuration file: /etc/zabbix/zabbix_server.conf
 17259:20260402:103631.139 current database version (mandatory/optional): 06000000/06000055
 17259:20260402:103631.139 required mandatory version: 06000000
 17261:20260402:103631.156 starting HA manager
 17261:20260402:103631.175 HA manager started in active mode
 17259:20260402:103631.176 server #0 started [main process]
 17263:20260402:103631.177 server #1 started [service manager #1]
 17264:20260402:103631.177 server #2 started [configuration syncer #1]
 17270:20260402:103631.324 server #5 started [alerter #2]
 17271:20260402:103631.324 server #6 started [alerter #3]
 17276:20260402:103631.325 server #11 started [lld manager #1]
 17277:20260402:103631.326 server #12 started [lld worker #1]
 17278:20260402:103631.327 server #13 started [lld worker #2]
 17272:20260402:103631.327 server #7 started [preprocessing manager #1]
 17269:20260402:103631.328 server #4 started [alerter #1]
 17282:20260402:103631.331 server #16 started [http poller #1]
 17268:20260402:103631.332 server #3 started [alert manager #1]
 17280:20260402:103631.332 server #15 started [timer #1]
 17279:20260402:103631.333 server #14 started [housekeeper #1]
 17284:20260402:103631.334 server #17 started [discoverer #1]
 17285:20260402:103631.334 server #18 started [history syncer #1]
 17286:20260402:103631.335 server #19 started [history syncer #2]
 17287:20260402:103631.335 server #20 started [history syncer #3]
 17288:20260402:103631.336 server #21 started [history syncer #4]
 17291:20260402:103631.336 server #24 started [self-monitoring #1]
 17292:20260402:103631.337 server #25 started [task manager #1]
 17289:20260402:103631.343 server #22 started [escalator #1]
 17290:20260402:103631.345 server #23 started [proxy poller #1]
 17306:20260402:103631.351 server #29 started [poller #4]
 17303:20260402:103631.352 server #26 started [poller #1]
 17307:20260402:103631.357 server #30 started [poller #5]
 17305:20260402:103631.383 server #28 started [poller #3]
 17304:20260402:103631.385 server #27 started [poller #2]
 17311:20260402:103631.387 server #34 started [trapper #3]
 17308:20260402:103631.391 server #31 started [unreachable poller #1]
 17312:20260402:103631.392 server #35 started [trapper #4]
 17309:20260402:103631.399 server #32 started [trapper #1]
 17310:20260402:103631.403 server #33 started [trapper #2]
 17273:20260402:103631.425 server #8 started [preprocessing worker #1]
 17274:20260402:103631.425 server #9 started [preprocessing worker #2]
 17275:20260402:103631.425 server #10 started [preprocessing worker #3]
 17319:20260402:103631.431 server #36 started [trapper #5]
 17320:20260402:103631.433 server #37 started [icmp pinger #1]
 17321:20260402:103631.445 server #38 started [alert syncer #1]
 17322:20260402:103631.447 server #39 started [history poller #1]
 17324:20260402:103631.451 server #40 started [history poller #2]
 17326:20260402:103631.456 server #42 started [history poller #4]
 17325:20260402:103631.458 server #41 started [history poller #3]
 17333:20260402:103631.466 server #46 started [odbc poller #1]
 17330:20260402:103631.474 server #43 started [history poller #5]
 17331:20260402:103631.475 server #44 started [availability manager #1]
 17332:20260402:103631.475 server #45 started [trigger housekeeper #1]
 17259:20260402:103641.957 Got signal [signal:15(SIGTERM),sender_pid:17347,sender_uid:0,reason:0]. Exiting ...
 17261:20260402:103642.163 HA manager has been paused
 17285:20260402:103642.163 syncing history data in progress... 
 17285:20260402:103642.163 syncing history data done
 17261:20260402:103643.245 HA manager has been stopped
 17259:20260402:103643.260 syncing trend data...
 17259:20260402:103643.265 syncing trend data done
 17259:20260402:103643.266 Zabbix Server stopped. Zabbix 6.0.45 (revision d8c5768f7d0).
 17367:20260402:103643.309 Starting Zabbix Server. Zabbix 6.0.45 (revision d8c5768f7d0).
 17367:20260402:103643.309 ****** Enabled features ******
 17367:20260402:103643.309 SNMP monitoring:           YES
 17367:20260402:103643.309 IPMI monitoring:           YES
 17367:20260402:103643.309 Web monitoring:            YES
 17367:20260402:103643.309 VMware monitoring:         YES
 17367:20260402:103643.309 SMTP authentication:       YES
 17367:20260402:103643.309 ODBC:                      YES
 17367:20260402:103643.309 SSH support:               YES
 17367:20260402:103643.309 IPv6 support:              YES
 17367:20260402:103643.309 TLS support:               YES
 17367:20260402:103643.309 ******************************
 17367:20260402:103643.309 using configuration file: /etc/zabbix/zabbix_server.conf
 17367:20260402:103643.337 current database version (mandatory/optional): 06000000/06000055
 17367:20260402:103643.337 required mandatory version: 06000000
 17370:20260402:103643.347 starting HA manager
 17370:20260402:103643.372 HA manager started in active mode
 17367:20260402:103643.372 server #0 started [main process]
 17372:20260402:103643.373 server #1 started [service manager #1]
 17373:20260402:103643.374 server #2 started [configuration syncer #1]
 17379:20260402:103643.523 server #5 started [alerter #2]
 17380:20260402:103643.523 server #6 started [alerter #3]
 17381:20260402:103643.523 server #7 started [preprocessing manager #1]
 17382:20260402:103643.524 server #8 started [preprocessing worker #1]
 17383:20260402:103643.524 server #9 started [preprocessing worker #2]
 17385:20260402:103643.524 server #11 started [lld manager #1]
 17386:20260402:103643.525 server #12 started [lld worker #1]
 17387:20260402:103643.526 server #13 started [lld worker #2]
 17390:20260402:103643.527 server #15 started [timer #1]
 17378:20260402:103643.527 server #4 started [alerter #1]
 17384:20260402:103643.528 server #10 started [preprocessing worker #3]
 17392:20260402:103643.528 server #17 started [discoverer #1]
 17394:20260402:103643.528 server #18 started [history syncer #1]
 17377:20260402:103643.529 server #3 started [alert manager #1]
 17391:20260402:103643.531 server #16 started [http poller #1]
 17388:20260402:103643.532 server #14 started [housekeeper #1]
 17401:20260402:103643.533 server #21 started [history syncer #4]
 17400:20260402:103643.539 server #20 started [history syncer #3]
 17398:20260402:103643.540 server #19 started [history syncer #2]
 17407:20260402:103643.544 server #24 started [self-monitoring #1]
 17408:20260402:103643.544 server #25 started [task manager #1]
 17406:20260402:103643.547 server #23 started [proxy poller #1]
 17411:20260402:103643.549 server #28 started [poller #3]
 17405:20260402:103643.550 server #22 started [escalator #1]
 17412:20260402:103643.552 server #29 started [poller #4]
 17415:20260402:103643.553 server #32 started [trapper #1]
 17416:20260402:103643.555 server #33 started [trapper #2]
 17417:20260402:103643.557 server #34 started [trapper #3]
 17409:20260402:103643.576 server #26 started [poller #1]
 17410:20260402:103643.584 server #27 started [poller #2]
 17426:20260402:103643.585 server #35 started [trapper #4]
 17427:20260402:103643.589 server #36 started [trapper #5]
 17428:20260402:103643.599 server #37 started [icmp pinger #1]
 17413:20260402:103643.601 server #30 started [poller #5]
 17414:20260402:103643.603 server #31 started [unreachable poller #1]
 17429:20260402:103643.612 server #38 started [alert syncer #1]
 17432:20260402:103643.659 server #40 started [history poller #2]
 17433:20260402:103643.662 server #41 started [history poller #3]
 17434:20260402:103643.664 server #42 started [history poller #4]
 17431:20260402:103643.665 server #39 started [history poller #1]
 17435:20260402:103643.676 server #43 started [history poller #5]
 17436:20260402:103643.680 server #44 started [availability manager #1]
 17437:20260402:103643.685 server #45 started [trigger housekeeper #1]
 17438:20260402:103643.695 server #46 started [odbc poller #1]
root@myvm:/home/student1# ^C
root@myvm:/home/student1# 
