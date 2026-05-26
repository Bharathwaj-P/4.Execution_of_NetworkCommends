# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
## 1.IPCONFIG
```

C:\Users\yuvasri>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::6c48:1823:5ed7:b16d%5
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
```
## 2.HOSTNAME:
```
C:\Users\yuvasri>hostname
LAPTOP-I5EN8JVF
```
## 3.TRACERT:
```

C:\Users\yuvasri>tracert

Usage: tracert [-d] [-h maximum_hops] [-j host-list] [-w timeout]
               [-R] [-S srcaddr] [-4] [-6] target_name

Options:
    -d                 Do not resolve addresses to hostnames.
    -h maximum_hops    Maximum number of hops to search for target.
    -j host-list       Loose source route along host-list (IPv4-only).
    -w timeout         Wait timeout milliseconds for each reply.
    -R                 Trace round-trip path (IPv6-only).
    -S srcaddr         Source address to use (IPv6-only).
    -4                 Force using IPv4.
    -6                 Force using IPv6.
```
##  4.PING:
```

C:\Users\yuvasri>ping www.google.com

Pinging www.google.com [2001:4860:4827:7700::] with 32 bytes of data:
Request timed out.
Reply from 2001:4860:4827:7700::: time=55ms
Reply from 2001:4860:4827:7700::: time=153ms
Reply from 2001:4860:4827:7700::: time=65ms

Ping statistics for 2001:4860:4827:7700:::
    Packets: Sent = 4, Received = 3, Lost = 1 (25% loss),
Approximate round trip times in milli-seconds:
    Minimum = 55ms, Maximum = 153ms, Average = 91ms
```
## 5.NETSTAT
```
C:\Users\yuvasri>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:55953        LAPTOP-I5EN8JVF:59970  ESTABLISHED
  TCP    127.0.0.1:59970        LAPTOP-I5EN8JVF:55953  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:49440  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:50553  lb-140-82-112-21-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:50798  sm-in-f188:5228        ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:52797  246:https              ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:52800  [64:ff9b::2854:5528]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:52801  [2606:4700:4407::ac40:92d7]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53747  ec2-52-6-79-11:https   CLOSE_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53755  [2606:4700:7::1fd]:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53756  pnmaaa-ba-in-x03:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53757  [2403:8600:80c0:4a::e62:1009]:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53758  [64:ff9b::489a:762]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53759  a184-28-109-248:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53760  [64:ff9b::6246:c0e0]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53761  [64:ff9b::6246:c0e0]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:53764  [64:ff9b::142a:4155]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:54126  [2603:1046:c04:1049::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:54273  ec2-54-146-40-28:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:54649  lb-140-82-112-26-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:54650  [64:ff9b::142a:4158]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:55886  [64:ff9b::3469:e827]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56788  bingforbusiness:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56789  [2603:1040:a06:3::13]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56790  [2603:1040:a06:3::13]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56791  bingforbusiness:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56793  g2600-14e1-0018-006d-0000-0000-0000-0000:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:56794  [2403:8600:80c0:4a::e62:1008]:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:57799  246:https              ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:58424  [2602:f79a::2]:https   ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:59302  server-99-86-182-37:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:59564  [64:ff9b::14cf:4955]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:59567  [2603:1030:10:12::387]:https  SYN_SENT
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:60350  ec2-18-233-84-75:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:60673  ec2-98-95-238-75:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:62055  [2620:1ec:50::12]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:62615  [2602:f79a::1]:https   ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:62851  ec2-18-233-84-75:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:63489  whatsapp-cdn6-shv-02-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:412:2516:f3c4]:63751  [2603:1040:a06:6::]:https  ESTABLISHED
```
## 6.SYSTEMINFO:
```

C:\Users\yuvasri>systeminfo

Host Name:                     LAPTOP-I5EN8JVF
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              yuvasri
Registered Organization:       HP
Product ID:                    00342-42708-78925-AAOEM
Original Install Date:         29-08-2025, 00:18:40
System Boot Time:              25-05-2026, 18:35:11
System Manufacturer:           HP
System Model:                  HP Laptop 15-fd1xxx
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  AMI F.06, 24-06-2024
Windows Directory:             C:\WINDOWS
System Directory:              C:\WINDOWS\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,801 MB
Available Physical Memory:     2,783 MB
Virtual Memory: Max Size:      27,577 MB
Virtual Memory: Available:     11,057 MB
Virtual Memory: In Use:        16,520 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\LAPTOP-I5EN8JVF
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5087051
                               [02]: KB5054156
                               [03]: KB5089549
                               [04]: KB5092762
Network Card(s):               3 NIC(s) Installed.
                               [01]: Realtek RTL8852BE WiFi 6 802.11ax PCIe Adapter
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.187.134
                                     [02]: fe80::95c8:bca0:3ccf:930a
                                     [03]: 2403:8600:c090:42:0:412:2516:f3c4
                               [02]: Bluetooth Device (Personal Area Network)
                                     Connection Name: Bluetooth Network Connection
                                     Status:          Media disconnected
                               [03]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::6c48:1823:5ed7:b16d
Virtualization-based security: Status: Running
                               Required Security Properties:
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                               Services Running:
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.
```
## 7.GETMAC:
```

C:\Users\yuvasri>getmac

Physical Address    Transport Name
=================== ==========================================================
C0-BF-BE-1A-BD-8E   \Device\Tcpip_{F4729B65-5615-4669-9C0B-D11119FBEBE1}
C0-BF-BE-1A-BD-8F   Media disconnected
0A-00-27-00-00-05   \Device\Tcpip_{23556052-9A66-4DFC-8D5C-64426B640C15}
```
## 8.TASKLIST:
```

C:\Users\yuvasri>tasklist

Image Name                     PID Session Name        Session#    Mem Usage
========================= ======== ================ =========== ============
System Idle Process              0 Services                   0          8 K
System                           4 Services                   0      5,324 K
Secure System                  260 Services                   0     56,996 K
Registry                       304 Services                   0     57,196 K
smss.exe                       940 Services                   0      1,560 K
csrss.exe                     1300 Services                   0      7,104 K
wininit.exe                   1408 Services                   0      8,768 K
csrss.exe                     1416 Console                    1      7,720 K
winlogon.exe                  1476 Console                    1     17,332 K
services.exe                  1548 Services                   0     20,908 K
LsaIso.exe                    1568 Services                   0      4,072 K
lsass.exe                     1580 Services                   0     36,860 K
svchost.exe                   1708 Services                   0     47,932 K
fontdrvhost.exe               1748 Services                   0      3,880 K
fontdrvhost.exe               1756 Console                    1      5,140 K
WUDFHost.exe                  1796 Services                   0     21,700 K
svchost.exe                   1880 Services                   0     23,092 K
svchost.exe                   1932 Services                   0     11,096 K
WUDFHost.exe                  1984 Services                   0     17,308 K
dwm.exe                       2036 Console                    1   2,93,944 K
WUDFHost.exe                  1280 Services                   0     12,016 K
WUDFHost.exe                  1600 Services                   0     12,400 K
svchost.exe                   2136 Services                   0      8,620 K
svchost.exe                   2180 Services                   0      7,220 K
svchost.exe                   2192 Services                   0     11,176 K
svchost.exe                   2204 Services                   0     15,572 K
svchost.exe                   2212 Services                   0      6,956 K
svchost.exe                   2368 Services                   0     11,488 K
svchost.exe                   2396 Services                   0     18,444 K
svchost.exe                   2432 Services                   0     14,916 K
svchost.exe                   2472 Services                   0     13,956 K
svchost.exe                   2480 Services                   0     16,112 K
svchost.exe                   2492 Services                   0     14,632 K
svchost.exe                   2620 Services                   0     12,356 K
svchost.exe                   2660 Services                   0     23,068 K
svchost.exe                   2672 Services                   0      7,700 K
svchost.exe                   2724 Services                   0     10,932 K
svchost.exe                   2740 Services                   0     27,676 K
svchost.exe                   3068 Services                   0     15,256 K
SynTPEnhService.exe           3280 Services                   0     14,416 K
svchost.exe                   3384 Services                   0     14,156 K
svchost.exe                   3460 Services                   0     25,604 K
svchost.exe                   3496 Services                   0      7,716 K
svchost.exe                   3504 Services                   0     19,972 K
svchost.exe                   3512 Services                   0     10,864 K
Memory Compression            3624 Services                   0  10,46,336 K
svchost.exe                   3664 Services                   0     12,420 K
svchost.exe                   3752 Services                   0     13,500 K
svchost.exe                   3760 Services                   0      9,856 K
TouchpointAnalyticsClient     3776 Services                   0   1,37,628 K
DiagsCap.exe                  3784 Services                   0     20,964 K
AppHelperCap.exe              3788 Services                   0     30,748 K
NetworkCap.exe                3804 Services                   0     32,200 K
SysInfoCap.exe                3812 Services                   0   1,25,788 K
hp-one-agent-service.exe      3932 Services                   0     39,996 K
svchost.exe                   4088 Services                   0     25,144 K
svchost.exe                   3020 Services                   0     21,268 K
svchost.exe                   3744 Services                   0      9,256 K
svchost.exe                   4264 Services                   0     31,228 K
svchost.exe                   4368 Services                   0     43,744 K
svchost.exe                   4532 Services                   0     18,264 K
svchost.exe                   4592 Services                   0     30,044 K
sihost.exe                    4696 Console                    1     55,960 K
svchost.exe                   4740 Services                   0     19,168 K
svchost.exe                   4752 Console                    1     47,856 K
svchost.exe                   4800 Console                    1     11,740 K
svchost.exe                   4872 Services                   0     11,604 K
svchost.exe                   4900 Console                    1     45,568 K
ctfmon.exe                    5052 Console                    1     40,520 K
svchost.exe                   5088 Services                   0     29,108 K
OmenInstallMonitor.exe        5096 Console                    1      8,068 K
SystemOptimizer.exe           5112 Console                    1     11,176 K
OverlayHelper.exe             3100 Console                    1     23,812 K
svchost.exe                   5328 Services                   0     13,504 K
svchost.exe                   5440 Services                   0     17,084 K
svchost.exe                   5492 Services                   0     32,976 K
svchost.exe                   5684 Services                   0     20,572 K
spoolsv.exe                   5788 Services                   0     19,428 K
svchost.exe                   5912 Services                   0     10,716 K
HPCommRecovery.exe            6116 Services                   0     28,328 K
DtsApo4Service.exe            6128 Services                   0     23,112 K
ipfsvc.exe                    5012 Services                   0     10,424 K
svchost.exe                   5296 Services                   0     40,328 K
IntelAudioService.exe         5528 Services                   0     32,228 K
svchost.exe                   5752 Services                   0     83,512 K
svchost.exe                   5744 Services                   0     11,348 K
jtagserver.exe                5676 Services                   0      6,192 K
svchost.exe                   5900 Services                   0      7,608 K
RtkAudUService64.exe          6152 Services                   0     23,528 K
HPPrintScanDoctorService.     6176 Services                   0     23,100 K
svchost.exe                   6188 Services                   0     16,332 K
RtkBtManServ.exe              6196 Services                   0     10,076 K
svchost.exe                   6212 Services                   0     32,508 K
WMIRegistrationService.ex     6224 Services                   0     15,928 K
taskhostw.exe                 6232 Console                    1     24,556 K
svchost.exe                   6240 Services                   0     12,040 K
svchost.exe                   6280 Services                   0     15,504 K
OfficeClickToRun.exe          6292 Services                   0     55,864 K
unsecapp.exe                  6320 Services                   0     11,080 K
MsMpEng.exe                   6336 Services                   0   3,16,416 K
svchost.exe                   6584 Services                   0     12,588 K
ipf_uf.exe                    6596 Services                   0      9,928 K
MpDefenderCoreService.exe     6608 Services                   0     28,268 K
servicehost.exe               6680 Services                   0     49,112 K
WmiPrvSE.exe                  6624 Services                   0     30,852 K
svchost.exe                   7184 Services                   0      9,496 K
svchost.exe                   7268 Services                   0     16,236 K
NgcIso.exe                    7692 Services                   0      4,340 K
svchost.exe                   7768 Services                   0      8,992 K
uihost.exe                    8792 Console                    1     45,776 K
ipf_helper.exe                9180 Console                    1     12,772 K
RtkAudUService64.exe          5232 Console                    1     21,352 K
svchost.exe                   5544 Services                   0     40,012 K
svchost.exe                   8932 Services                   0     33,100 K
svchost.exe                   3700 Services                   0     10,388 K
SynTPEnh.exe                  9428 Console                    1     27,228 K
IntelGraphicsSoftware.Ser     9516 Services                   0     43,876 K
explorer.exe                  9708 Console                    1   5,12,764 K
svchost.exe                   9888 Services                   0     28,620 K
CrossDeviceResume.exe        10072 Console                    1     69,396 K
AggregatorHost.exe            9400 Services                   0     15,264 K
svchost.exe                   9992 Services                   0     12,236 K
PresentMonService.exe        10620 Services                   0     14,848 K
conhost.exe                  10632 Services                   0      6,312 K
SearchIndexer.exe            10872 Services                   0     42,464 K
svchost.exe                  10984 Services                   0     37,020 K
CrossDeviceService.exe       11016 Console                    1   1,59,012 K
svchost.exe                  11024 Services                   0     30,756 K
svchost.exe                   7760 Console                    1     29,104 K
DtsServiceUtility.exe        11356 Console                    1     21,456 K
conhost.exe                  11372 Console                    1      6,932 K
SearchHost.exe               11716 Console                    1   1,76,228 K
StartMenuExperienceHost.e    11724 Console                    1   2,01,880 K
Widgets.exe                  12048 Console                    1     60,728 K
RuntimeBroker.exe            12136 Console                    1     78,028 K
svchost.exe                  12200 Console                    1     37,544 K
RuntimeBroker.exe            12308 Console                    1     14,668 K
WidgetService.exe            12388 Console                    1     25,092 K
backgroundTaskHost.exe       12960 Console                    1      2,516 K
msedgewebview2.exe           13660 Console                    1   1,29,276 K
msedgewebview2.exe           13800 Console                    1     13,052 K
msedgewebview2.exe           13436 Console                    1     46,040 K
msedgewebview2.exe            3356 Console                    1   1,46,980 K
msedgewebview2.exe           13748 Console                    1     20,604 K
msedgewebview2.exe           14568 Console                    1   1,24,532 K
svchost.exe                  14896 Console                    1     23,448 K
ReconsentNotification.exe    11904 Console                    1     55,712 K
NisSrv.exe                   15600 Services                   0     14,808 K
svchost.exe                  15824 Services                   0     13,252 K
TextInputHost.exe            16076 Console                    1   2,06,400 K
PhoneExperienceHost.exe      16376 Console                    1   2,50,032 K
svchost.exe                   9884 Services                   0      9,388 K
svchost.exe                   8260 Console                    1     19,324 K
WhatsApp.Root.exe            16848 Console                    1   2,58,540 K
svchost.exe                  16868 Services                   0     17,208 K
RuntimeBroker.exe             2152 Console                    1     14,176 K
SecurityHealthSystray.exe    15912 Console                    1     14,140 K
SecurityHealthService.exe    16864 Services                   0     30,796 K
RtkAudUService64.exe         17144 Console                    1     25,520 K
HP.ContextAware.exe          17440 Console                    1     58,724 K
OneDrive.exe                  9696 Console                    1   1,95,176 K
svchost.exe                   2264 Services                   0     11,284 K
FileSyncHelper.exe           19988 Services                   0     31,216 K
dasHost.exe                  18820 Services                   0     25,584 K
dasHost.exe                  19584 Services                   0     12,864 K
HPSystemEventUtilityBackg    17648 Console                    1     75,520 K
unsecapp.exe                 19304 Console                    1     12,432 K
HPMediaNetwork.exe           14668 Console                    1     51,932 K
svchost.exe                  19544 Services                   0     28,968 K
Notion.exe                   17660 Console                    1   1,31,272 K
Notion.exe                   20644 Console                    1   1,10,080 K
Notion.exe                   20688 Console                    1     70,936 K
Notion.exe                   20868 Console                    1     64,356 K
Notion.exe                   21012 Console                    1     67,760 K
Notion.exe                   21128 Console                    1   2,58,392 K
Notion.exe                   21428 Console                    1   1,94,832 K
Canva.exe                    20460 Console                    1     32,036 K
OmenCommandCenterBackgrou     6372 Console                    1   2,82,668 K
Canva.exe                     7708 Console                    1     44,996 K
BridgeCommunication.exe       9920 Console                    1     40,796 K
Grammarly.Desktop.exe        18408 Console                    1   3,34,008 K
mscopilot.exe                12984 Console                    1   1,10,996 K
mscopilot.exe                18424 Console                    1     12,896 K
mscopilot.exe                15236 Console                    1     46,144 K
mscopilot.exe                13196 Console                    1     40,828 K
mscopilot.exe                12672 Console                    1     18,720 K
Superhuman.WebUI.exe          7572 Console                    1     40,080 K
conhost.exe                  12176 Console                    1      8,112 K
msedgewebview2.exe            5292 Console                    1   1,23,008 K
msedgewebview2.exe           15608 Console                    1     13,252 K
msedgewebview2.exe           18456 Console                    1     56,048 K
msedgewebview2.exe            8088 Console                    1     46,588 K
msedgewebview2.exe           19960 Console                    1     19,384 K
msedgewebview2.exe            7720 Console                    1   1,11,376 K
msedgewebview2.exe           22608 Console                    1   1,26,820 K
msedgewebview2.exe           22660 Console                    1     13,176 K
msedgewebview2.exe           22880 Console                    1     67,340 K
msedgewebview2.exe           22888 Console                    1     44,036 K
msedgewebview2.exe           22928 Console                    1     19,816 K
LinkedIn.exe                 24348 Console                    1   1,90,936 K
RuntimeBroker.exe            24512 Console                    1     14,740 K
msedgewebview2.exe           24572 Console                    1   1,85,416 K
msedgewebview2.exe           13288 Console                    1     13,412 K
msedgewebview2.exe            4032 Console                    1   1,16,504 K
msedgewebview2.exe           12316 Console                    1     54,096 K
msedgewebview2.exe           11568 Console                    1     20,248 K
svchost.exe                  11616 Console                    1     16,416 K
svchost.exe                  24704 Services                   0     12,512 K
RuntimeBroker.exe            24808 Console                    1     23,776 K
svchost.exe                  25036 Services                   0     34,112 K
svchost.exe                  25200 Services                   0     10,572 K
svchost.exe                  25340 Services                   0     15,100 K
svchost.exe                  25392 Services                   0     16,708 K
msedgewebview2.exe           25436 Console                    1   1,13,636 K
msedgewebview2.exe           25492 Console                    1     13,436 K
svchost.exe                  17400 Services                   0     45,624 K
msedgewebview2.exe            7876 Console                    1   1,50,740 K
msedgewebview2.exe            7884 Console                    1     26,544 K
msedgewebview2.exe           24796 Console                    1      5,348 K
svchost.exe                  24996 Services                   0     16,376 K
svchost.exe                  26272 Services                   0     33,564 K
ONENOTEM.EXE                  8608 Console                    1      6,696 K
msedgewebview2.exe            4828 Console                    1   4,03,620 K
msedgewebview2.exe           12756 Console                    1   3,81,764 K
msedgewebview2.exe           26984 Console                    1     74,612 K
msedgewebview2.exe           24524 Console                    1      4,852 K
AppActions.exe                6908 Console                    1     55,328 K
msedgewebview2.exe           23852 Console                    1     25,092 K
ApplicationFrameHost.exe     26480 Console                    1     62,084 K
svchost.exe                  28368 Services                   0     17,788 K
msedgewebview2.exe           31156 Console                    1     43,116 K
msedgewebview2.exe           30488 Console                    1     65,636 K
msedgewebview2.exe            3472 Console                    1     39,084 K
msedgewebview2.exe           32060 Console                    1     42,984 K
svchost.exe                   4884 Services                   0     12,940 K
svchost.exe                  26088 Services                   0     21,960 K
svchost.exe                   8904 Console                    1     16,372 K
ShellExperienceHost.exe      23244 Console                    1     97,828 K
RuntimeBroker.exe            17148 Console                    1     24,444 K
dllhost.exe                  25084 Console                    1      9,484 K
svchost.exe                  26160 Services                   0     14,388 K
svchost.exe                  12360 Services                   0     33,216 K
WmiApSrv.exe                 34512 Services                   0     12,204 K
SafeExamBrowser.Service.e    35756 Services                   0     28,932 K
svchost.exe                  24760 Services                   0     40,620 K
FileCoAuth.exe               17180 Console                    1     42,804 K
svchost.exe                   3552 Services                   0      9,336 K
OneDrive.Sync.Service.exe    35608 Console                    1     32,520 K
chrome.exe                   28976 Console                    1   2,65,888 K
chrome.exe                   27836 Console                    1      9,900 K
chrome.exe                   26424 Console                    1   2,89,092 K
chrome.exe                   21412 Console                    1     60,272 K
chrome.exe                   35404 Console                    1     21,224 K
chrome.exe                   31236 Console                    1     92,372 K
cmd.exe                       2640 Console                    1      5,644 K
conhost.exe                  25928 Console                    1      9,756 K
browserhost.exe              11768 Console                    1     18,900 K
chrome.exe                   23460 Console                    1     60,808 K
chrome.exe                   30312 Console                    1     41,220 K
SystemSettings.exe           31232 Console                    1      3,888 K
UserOOBEBroker.exe           32556 Console                    1     11,284 K
chrome.exe                   29944 Console                    1   1,23,244 K
sppsvc.exe                   33368 Services                   0     15,332 K
chrome.exe                   31736 Console                    1   3,12,576 K
chrome.exe                    9820 Console                    1     57,384 K
chrome.exe                   19092 Console                    1     21,212 K
cmd.exe                      31244 Console                    1     32,236 K
conhost.exe                   7888 Console                    1     10,244 K
OpenConsole.exe              18532 Console                    1     16,284 K
WindowsTerminal.exe          12436 Console                    1   1,38,144 K
Notepad.exe                  27260 Console                    1     17,240 K
Notepad.exe                  32336 Console                    1   2,07,648 K
SnippingTool.exe              1080 Console                    1   1,21,660 K
ShellHost.exe                33172 Console                    1   1,98,560 K
WmiPrvSE.exe                 19440 Services                   0     27,340 K
Photos.exe                    6868 Console                    1   2,22,380 K
Photos.exe                   15204 Console                    1   1,39,204 K
svchost.exe                  22800 Services                   0      8,836 K
chrome.exe                    4320 Console                    1   1,54,804 K
chrome.exe                   19556 Console                    1   1,74,096 K
chrome.exe                   17748 Console                    1   2,36,412 K
cmd.exe                      12280 Console                    1      8,364 K
conhost.exe                  22016 Console                    1     10,240 K
OpenConsole.exe              34588 Console                    1     22,368 K
svchost.exe                  24528 Services                   0     10,124 K
msedge.exe                   10816 Console                    1   1,52,460 K
msedge.exe                   11920 Console                    1     13,400 K
msedge.exe                   29472 Console                    1     94,508 K
msedge.exe                    1284 Console                    1     39,968 K
msedge.exe                    8728 Console                    1     20,592 K
HPSystemEventUtilityHost.     9504 Console                    1     41,992 K
chrome.exe                   27024 Console                    1     77,152 K
backgroundTaskHost.exe       31024 Console                    1     63,096 K
RuntimeBroker.exe            11528 Console                    1     32,624 K
msedgewebview2.exe           28708 Console                    1     80,264 K
svchost.exe                  34584 Services                   0     13,748 K
chrome.exe                    4668 Console                    1     32,476 K
msiexec.exe                  17868 Services                   0     20,656 K
MoUsoCoreWorker.exe          23020 Services                   0     33,336 K
svchost.exe                  31688 Services                   0     49,804 K
WmiPrvSE.exe                 21516 Services                   0     15,164 K
svchost.exe                  23724 Services                   0      8,912 K
TrustedInstaller.exe         32584 Services                   0     10,008 K
TiWorker.exe                 25176 Services                   0     18,508 K
msedgewebview2.exe           34164 Console                    1     77,268 K
tasklist.exe                  2404 Console                    1     11,852 K
```
## 9.NSLOOKUP
```
C:\Users\yuvasri>nslookup
Default Server:  UnKnown
Address:  2403:8600:c090:42:a000::200
```
## 10.ARP:
```

C:\Users\yuvasri>arp -a

Interface: 192.168.56.1 --- 0x5
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  224.0.1.60            01-00-5e-00-01-3c     static
  224.0.2.3             01-00-5e-00-02-03     static
  224.77.77.77          01-00-5e-4d-4d-4d     static
  225.16.8.68           01-00-5e-10-08-44     static
  230.0.0.1             01-00-5e-00-00-01     static
  239.192.152.143       01-00-5e-40-98-8f     static
  239.255.67.250        01-00-5e-7f-43-fa     static
  239.255.102.18        01-00-5e-7f-66-12     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  239.255.255.253       01-00-5e-7f-ff-fd     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

Interface: 169.254.187.134 --- 0x12
  Internet Address      Physical Address      Type
  169.254.7.15          98-bd-80-d9-90-db     dynamic
  169.254.7.103         ac-45-ef-06-ac-ca     dynamic
  169.254.28.75         e0-2e-0b-34-62-19     dynamic
  169.254.53.55         e0-2e-0b-29-aa-36     dynamic
  169.254.53.69         38-a2-8c-40-24-b3     dynamic
  169.254.59.6          50-bb-b5-04-34-9a     dynamic
  169.254.69.71         c0-35-32-1c-a9-4d     dynamic
  169.254.73.137        f4-8e-38-9e-76-62     dynamic
  169.254.80.217        e0-2e-0b-34-6e-d0     dynamic
  169.254.91.33         e0-2e-0b-34-31-68     dynamic
  169.254.139.71        68-34-21-83-a9-d7     dynamic
  169.254.148.228       e0-2e-0b-7b-1b-1e     dynamic
  169.254.169.185       68-34-21-81-83-5a     dynamic
  169.254.182.31        c8-5e-a9-97-a1-6c     dynamic
  169.254.182.255       fc-6d-77-6b-f2-92     dynamic
  169.254.191.134       d8-44-89-e7-23-25     dynamic
  169.254.196.236       e0-2e-0b-38-3f-51     dynamic
  169.254.210.224       10-6f-d9-89-d9-f7     dynamic
  169.254.222.144       04-d3-b0-ee-dd-42     dynamic
  169.254.224.3         3c-a0-67-8f-1c-13     dynamic
  169.254.225.99        00-e0-4c-68-11-3e     dynamic
  169.254.252.135       e0-2e-0b-7c-ff-38     dynamic
  169.254.255.255       ff-ff-ff-ff-ff-ff     static
  192.168.5.15          34-9f-7b-d6-e2-31     dynamic
  192.168.29.100        9c-93-4e-da-54-df     dynamic
  192.168.29.135        f4-8e-38-9f-3a-8a     dynamic
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  224.77.77.77          01-00-5e-4d-4d-4d     static
  225.16.8.68           01-00-5e-10-08-44     static
  239.192.152.143       01-00-5e-40-98-8f     static
  239.255.67.250        01-00-5e-7f-43-fa     static
  239.255.102.18        01-00-5e-7f-66-12     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  239.255.255.253       01-00-5e-7f-ff-fd     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static
```

## Result
Thus Execution of Network commands Performed
