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
[Command Prompt.txt](https://github.com/user-attachments/files/27296989/Command.Prompt.txt)
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\yuvasri>ipconfig

Windows IP Configuration


Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:7b8e:70:a7c7:db47:52c2:86b6
   Temporary IPv6 Address. . . . . . : 2401:4900:7b8e:70:a1d7:6c4:4a7d:e824
   Link-local IPv6 Address . . . . . : fe80::95c8:bca0:3ccf:930a%17
   IPv4 Address. . . . . . . . . . . : 10.129.146.162
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::9854:faff:fec8:ab9c%17
                                       10.129.146.23

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\yuvasri>ping chatgpt.com

Pinging chatgpt.com [2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4] with 32 bytes of data:
Reply from 2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4: time=13ms
Reply from 2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4: time=42ms
Reply from 2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4: time=20ms
Reply from 2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4: time=26ms

Ping statistics for 2606:4700:83b2:7cbc:c2a5:627:5ff2:75c4:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 13ms, Maximum = 42ms, Average = 25ms

C:\Users\yuvasri>

C:\Users\yuvasri>scannow
'scannow' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\yuvasri>tasklist

Image Name                     PID Session Name        Session#    Mem Usage
========================= ======== ================ =========== ============
System Idle Process              0 Services                   0          8 K
System                           4 Services                   0      5,888 K
Secure System                  260 Services                   0     64,240 K
Registry                       304 Services                   0     66,492 K
smss.exe                       916 Services                   0        412 K
csrss.exe                     1208 Services                   0      3,732 K
wininit.exe                   1384 Services                   0      2,308 K
csrss.exe                     1392 Console                    1      4,992 K
winlogon.exe                  1468 Console                    1      8,096 K
services.exe                  1520 Services                   0     11,844 K
LsaIso.exe                    1544 Services                   0      1,664 K
lsass.exe                     1552 Services                   0     24,972 K
svchost.exe                   1684 Services                   0     35,412 K
fontdrvhost.exe               1724 Console                    1      2,904 K
fontdrvhost.exe               1732 Services                   0      1,656 K
WUDFHost.exe                  1808 Services                   0     10,628 K
svchost.exe                   1860 Services                   0     21,184 K
svchost.exe                   1904 Services                   0      6,316 K
dwm.exe                       1988 Console                    1   1,82,536 K
WUDFHost.exe                  2016 Services                   0      8,052 K
WUDFHost.exe                   956 Services                   0      3,368 K
WUDFHost.exe                  2068 Services                   0      6,128 K
svchost.exe                   2168 Services                   0      4,000 K
svchost.exe                   2184 Services                   0      2,724 K
svchost.exe                   2192 Services                   0      7,968 K
svchost.exe                   2260 Services                   0      5,128 K
svchost.exe                   2268 Services                   0     10,780 K
svchost.exe                   2276 Services                   0      9,912 K
svchost.exe                   2292 Services                   0      9,796 K
svchost.exe                   2432 Services                   0      8,036 K
svchost.exe                   2456 Services                   0      6,948 K
svchost.exe                   2464 Services                   0      7,704 K
svchost.exe                   2556 Services                   0      7,088 K
svchost.exe                   2588 Services                   0      6,164 K
svchost.exe                   2612 Services                   0      3,256 K
svchost.exe                   2648 Services                   0     19,772 K
svchost.exe                   2688 Services                   0      9,564 K
svchost.exe                   2984 Services                   0      5,972 K
svchost.exe                   2508 Services                   0      7,548 K
svchost.exe                   3108 Services                   0      9,004 K
svchost.exe                   3252 Services                   0     13,520 K
svchost.exe                   3372 Services                   0      5,636 K
svchost.exe                   3384 Services                   0     11,192 K
svchost.exe                   3580 Services                   0     12,052 K
SynTPEnhService.exe           3728 Services                   0      7,192 K
svchost.exe                   3736 Services                   0      4,864 K
svchost.exe                   3820 Services                   0     17,976 K
svchost.exe                   3856 Services                   0      6,308 K
svchost.exe                   3864 Services                   0      2,992 K
svchost.exe                   3884 Services                   0     14,520 K
svchost.exe                   4016 Services                   0      7,580 K
Memory Compression            4064 Services                   0   2,85,236 K
svchost.exe                   3792 Services                   0      6,680 K
AppHelperCap.exe              3748 Services                   0     18,844 K
DiagsCap.exe                  3780 Services                   0      7,524 K
NetworkCap.exe                3716 Services                   0     10,940 K
TouchpointAnalyticsClient     4100 Services                   0     58,460 K
SysInfoCap.exe                4108 Services                   0     43,328 K
svchost.exe                   4124 Services                   0      8,064 K
svchost.exe                   4276 Services                   0      4,008 K
svchost.exe                   4392 Services                   0     44,992 K
hp-one-agent-service.exe      4508 Services                   0     22,244 K
svchost.exe                   4532 Services                   0     14,132 K
svchost.exe                   4764 Services                   0     32,204 K
svchost.exe                   4840 Services                   0     25,140 K
unsecapp.exe                  5068 Services                   0      5,500 K
WmiPrvSE.exe                  4668 Services                   0     19,952 K
svchost.exe                   5176 Services                   0      4,860 K
svchost.exe                   5308 Services                   0      7,304 K
svchost.exe                   5372 Services                   0     16,160 K
svchost.exe                   5404 Services                   0      2,968 K
svchost.exe                   5428 Services                   0      9,924 K
spoolsv.exe                   5476 Services                   0      7,784 K
svchost.exe                   5528 Services                   0     18,928 K
svchost.exe                   5672 Services                   0      8,532 K
svchost.exe                   5712 Services                   0      2,676 K
svchost.exe                   5744 Services                   0      4,368 K
NgcIso.exe                    5800 Services                   0      1,692 K
HPCommRecovery.exe            5848 Services                   0     12,652 K
svchost.exe                   5856 Services                   0     41,304 K
DtsApo4Service.exe            5864 Services                   0      6,760 K
svchost.exe                   5872 Services                   0     42,356 K
HPPrintScanDoctorService.     5896 Services                   0     14,624 K
IntelAudioService.exe         5904 Services                   0     12,584 K
ipf_uf.exe                    5924 Services                   0      4,584 K
svchost.exe                   5936 Services                   0      7,760 K
jtagserver.exe                5956 Services                   0      2,180 K
ipfsvc.exe                    5968 Services                   0      4,280 K
svchost.exe                   5976 Services                   0      4,716 K
OfficeClickToRun.exe          5988 Services                   0     25,584 K
MpDefenderCoreService.exe     6040 Services                   0     21,976 K
RtkBtManServ.exe              5172 Services                   0      2,932 K
SafeExamBrowser.Service.e     5708 Services                   0      7,748 K
RtkAudUService64.exe          6196 Services                   0     10,560 K
svchost.exe                   6252 Services                   0      5,152 K
svchost.exe                   6268 Services                   0      2,432 K
WMIRegistrationService.ex     6312 Services                   0      4,196 K
MsMpEng.exe                   6328 Services                   0   2,44,556 K
svchost.exe                   6376 Services                   0     18,860 K
svchost.exe                   6852 Services                   0      5,804 K
svchost.exe                   8900 Services                   0     22,812 K
svchost.exe                   9056 Services                   0      3,252 K
AggregatorHost.exe            8380 Services                   0     10,104 K
svchost.exe                   6904 Services                   0     26,692 K
RtkAudUService64.exe          5844 Console                    1      8,516 K
svchost.exe                   5820 Services                   0      6,640 K
NisSrv.exe                    9232 Services                   0      6,848 K
svchost.exe                   6448 Services                   0     11,480 K
ipf_helper.exe                4264 Console                    1      5,436 K
sihost.exe                    3772 Console                    1     32,144 K
svchost.exe                   4516 Console                    1      5,880 K
svchost.exe                   9748 Console                    1     36,140 K
svchost.exe                   5188 Console                    1      3,568 K
svchost.exe                   8476 Console                    1     26,044 K
taskhostw.exe                 6320 Console                    1     14,652 K
svchost.exe                  10244 Services                   0     21,732 K
explorer.exe                 11004 Console                    1   2,75,712 K
svchost.exe                  11020 Services                   0      6,808 K
svchost.exe                   3916 Services                   0     19,728 K
SynTPEnh.exe                 10896 Console                    1     14,060 K
svchost.exe                   6912 Services                   0      8,996 K
CrossDeviceResume.exe        11360 Console                    1     23,276 K
svchost.exe                  12056 Services                   0     25,132 K
svchost.exe                  12140 Services                   0     28,700 K
SearchIndexer.exe            12316 Services                   0     38,232 K
CrossDeviceService.exe       12408 Console                    1   1,09,084 K
RuntimeBroker.exe            12868 Console                    1      4,160 K
svchost.exe                  12360 Console                    1     20,176 K
StartMenuExperienceHost.e    10432 Console                    1   1,85,756 K
SearchHost.exe               12268 Console                    1     98,620 K
Widgets.exe                  13544 Console                    1     55,896 K
RuntimeBroker.exe            13604 Console                    1     33,824 K
svchost.exe                  13648 Console                    1     11,580 K
svchost.exe                  14208 Services                   0     18,148 K
msedgewebview2.exe           14804 Console                    1     74,440 K
msedgewebview2.exe           14900 Console                    1      3,548 K
msedgewebview2.exe           15276 Console                    1   1,22,696 K
msedgewebview2.exe           15312 Console                    1     31,048 K
msedgewebview2.exe           14356 Console                    1     10,216 K
msedgewebview2.exe           15404 Console                    1   1,18,584 K
ReconsentNotification.exe    16328 Console                    1     28,416 K
ctfmon.exe                   16316 Console                    1     19,880 K
backgroundTaskHost.exe       13640 Console                    1        452 K
RuntimeBroker.exe             9984 Console                    1      6,236 K
svchost.exe                  16868 Console                    1     14,596 K
svchost.exe                  17176 Services                   0      3,088 K
svchost.exe                  17344 Console                    1      6,376 K
svchost.exe                  16696 Services                   0      6,764 K
TextInputHost.exe            16648 Console                    1     72,576 K
HP.ContextAware.exe          17812 Console                    1     30,800 K
SystemOptimizer.exe          18028 Console                    1     10,548 K
SecurityHealthSystray.exe    18384 Console                    1      5,856 K
SecurityHealthService.exe    18400 Services                   0     20,252 K
RtkAudUService64.exe           800 Console                    1     14,468 K
OneDrive.exe                  6080 Console                    1   1,16,180 K
svchost.exe                  17964 Services                   0      4,936 K
IntelGraphicsSoftware.Ser    13928 Services                   0     12,648 K
PresentMonService.exe        18248 Services                   0      3,404 K
conhost.exe                  10984 Services                   0      1,764 K
HPSystemEventUtilityBackg     3312 Console                    1     36,788 K
unsecapp.exe                 13248 Console                    1      7,808 K
HPMediaNetwork.exe            4996 Console                    1     24,868 K
WhatsApp.Root.exe            12436 Console                    1   2,42,900 K
RuntimeBroker.exe            18140 Console                    1      4,028 K
FileSyncHelper.exe           10908 Services                   0     16,600 K
BridgeCommunication.exe      19588 Console                    1     13,668 K
svchost.exe                  20120 Services                   0      2,804 K
dasHost.exe                  20460 Services                   0     20,952 K
dasHost.exe                  17788 Services                   0      7,484 K
Notion.exe                    9716 Console                    1     66,492 K
Notion.exe                   10312 Console                    1     27,632 K
Notion.exe                   10948 Console                    1     31,232 K
Notion.exe                    9468 Console                    1     22,052 K
Notion.exe                   11572 Console                    1     14,688 K
Notion.exe                    8944 Console                    1   1,90,116 K
Notion.exe                   12876 Console                    1   1,18,520 K
Notion.exe                   20628 Console                    1   1,61,488 K
WidgetService.exe            20892 Console                    1     10,112 K
msedgewebview2.exe           21404 Console                    1      9,776 K
msedgewebview2.exe           21432 Console                    1      3,708 K
msedgewebview2.exe           11396 Console                    1      6,188 K
msedgewebview2.exe           11892 Console                    1      3,008 K
msedgewebview2.exe           19584 Console                    1         20 K
msedgewebview2.exe           13400 Console                    1        608 K
OmenCommandCenterBackgrou    15356 Console                    1   2,31,940 K
svchost.exe                  17676 Services                   0     29,280 K
svchost.exe                  17152 Services                   0      5,504 K
svchost.exe                   6240 Services                   0      7,860 K
svchost.exe                  16416 Services                   0     10,180 K
svchost.exe                   6440 Services                   0     36,044 K
svchost.exe                  20136 Services                   0      8,736 K
svchost.exe                   5484 Console                    1     13,348 K
ApplicationFrameHost.exe     22280 Console                    1     27,808 K
Canva.exe                     9024 Console                    1      9,072 K
Canva.exe                     9424 Console                    1     12,728 K
OverlayHelper.exe            21936 Console                    1      6,616 K
OmenInstallMonitor.exe       10252 Console                    1      5,820 K
FileCoAuth.exe                6264 Console                    1     22,884 K
LinkedIn.exe                  4708 Console                    1     79,624 K
RuntimeBroker.exe             4652 Console                    1      4,028 K
msedgewebview2.exe           17092 Console                    1   1,47,588 K
msedgewebview2.exe            7496 Console                    1      3,676 K
msedgewebview2.exe           22416 Console                    1     47,056 K
msedgewebview2.exe           19096 Console                    1     35,596 K
msedgewebview2.exe           18592 Console                    1      8,632 K
msedgewebview2.exe           22648 Console                    1     58,928 K
msedgewebview2.exe            8428 Console                    1      4,044 K
msedgewebview2.exe            9188 Console                    1     13,348 K
msedgewebview2.exe           23160 Console                    1     21,792 K
msedgewebview2.exe           23188 Console                    1      2,656 K
msedgewebview2.exe           25068 Console                    1      5,116 K
msedgewebview2.exe           24284 Console                    1     14,088 K
PhoneExperienceHost.exe      17960 Console                    1   1,20,472 K
msedgewebview2.exe           21988 Console                    1      3,216 K
RuntimeBroker.exe            25660 Console                    1      9,716 K
ONENOTEM.EXE                 27332 Console                    1      3,364 K
svchost.exe                  20200 Services                   0      5,292 K
AppActions.exe               18008 Console                    1     16,152 K
Grammarly.Desktop.exe         9528 Console                    1   2,64,580 K
Grammarly.WebUI.exe          22860 Console                    1     20,072 K
conhost.exe                  10368 Console                    1      2,064 K
msedgewebview2.exe           21280 Console                    1     54,692 K
msedgewebview2.exe            6244 Console                    1      3,556 K
msedgewebview2.exe            5436 Console                    1     16,944 K
msedgewebview2.exe           25752 Console                    1     28,256 K
msedgewebview2.exe           24744 Console                    1      7,612 K
msedgewebview2.exe           21176 Console                    1     89,776 K
msedgewebview2.exe           15880 Console                    1     73,552 K
msedgewebview2.exe           15824 Console                    1      3,612 K
msedgewebview2.exe           15232 Console                    1     25,536 K
msedgewebview2.exe           17372 Console                    1     26,796 K
msedgewebview2.exe           10684 Console                    1      7,884 K
msedgewebview2.exe           27228 Console                    1     58,516 K
dllhost.exe                  17872 Console                    1      3,460 K
msedgewebview2.exe           16544 Console                    1     56,252 K
svchost.exe                  31300 Services                   0     16,636 K
ShellExperienceHost.exe      20236 Console                    1     44,720 K
RuntimeBroker.exe            19332 Console                    1     13,348 K
SDXHelper.exe                22228 Console                    1     32,740 K
OneDrive.Sync.Service.exe    19040 Console                    1     34,056 K
BridgeCommunication.exe      12980 Console                    1     17,944 K
hpqwmiex.exe                 20140 Services                   0      8,316 K
servicehost.exe              29288 Services                   0     36,056 K
uihost.exe                   24992 Console                    1     38,940 K
WmiApSrv.exe                  9192 Services                   0      8,072 K
msedgewebview2.exe           32648 Console                    1   7,73,308 K
msedgewebview2.exe            1672 Console                    1     45,952 K
msedgewebview2.exe           22812 Console                    1     45,880 K
msedgewebview2.exe           23156 Console                    1     80,628 K
msedgewebview2.exe           19740 Console                    1     61,368 K
SystemSettings.exe           24176 Console                    1        976 K
UserOOBEBroker.exe            8668 Console                    1      8,332 K
svchost.exe                  32172 Services                   0     56,256 K
svchost.exe                  13728 Services                   0      4,580 K
ShellHost.exe                29428 Console                    1   1,48,156 K
msedgewebview2.exe           27024 Console                    1     58,804 K
svchost.exe                  17008 Services                   0     28,400 K
msedge.exe                   10216 Console                    1   2,41,100 K
msedge.exe                    6568 Console                    1     10,220 K
msedge.exe                   26952 Console                    1   2,07,096 K
msedge.exe                   30008 Console                    1     52,728 K
msedge.exe                    7092 Console                    1     21,536 K
chrome.exe                   32980 Console                    1   2,81,236 K
chrome.exe                   22632 Console                    1     10,684 K
chrome.exe                    9456 Console                    1   6,98,824 K
chrome.exe                   28608 Console                    1     61,200 K
chrome.exe                   28728 Console                    1     27,652 K
chrome.exe                   10784 Console                    1   1,14,880 K
chrome.exe                   23516 Console                    1     96,680 K
chrome.exe                   21852 Console                    1   2,17,940 K
chrome.exe                   31812 Console                    1   1,23,880 K
cmd.exe                      29780 Console                    1      4,360 K
conhost.exe                  14836 Console                    1      9,724 K
browserhost.exe               7440 Console                    1     17,560 K
msedge.exe                   17720 Console                    1      4,744 K
chrome.exe                   29864 Console                    1     45,168 K
svchost.exe                  33604 Services                   0      9,076 K
chrome.exe                   30968 Console                    1   5,38,176 K
MoUsoCoreWorker.exe          32164 Services                   0     75,300 K
svchost.exe                  17488 Services                   0     97,656 K
WmiPrvSE.exe                 19148 Services                   0     23,868 K
WmiPrvSE.exe                 22956 Services                   0     16,180 K
svchost.exe                  14932 Services                   0      9,580 K
smartscreen.exe              13252 Console                    1     13,324 K
wuaucltcore.exe               7004 Services                   0     45,356 K
TrustedInstaller.exe         31940 Services                   0     10,776 K
TiWorker.exe                 28576 Services                   0  11,84,968 K
LockApp.exe                  16268 Console                    1     84,184 K
RuntimeBroker.exe            11244 Console                    1     50,528 K
HPSystemEventUtilityHost.    23420 Console                    1     44,712 K
msedge.exe                   10796 Console                    1   1,19,284 K
msedge.exe                   24092 Console                    1     35,824 K
msedge.exe                   18956 Console                    1     31,668 K
RuntimeBroker.exe            30024 Console                    1     31,860 K
svchost.exe                   3968 Services                   0      9,420 K
svchost.exe                  31984 Services                   0     10,580 K
cmd.exe                       9792 Console                    1      6,112 K
conhost.exe                   3264 Console                    1     10,616 K
OpenConsole.exe               7676 Console                    1     23,616 K
WindowsTerminal.exe          21732 Console                    1   1,36,388 K
chrome.exe                   25360 Console                    1     18,276 K
chrome.exe                   16136 Console                    1     61,912 K
chrome.exe                   25320 Console                    1     97,140 K
chrome.exe                   31188 Console                    1     52,596 K
chrome.exe                   29516 Console                    1     34,816 K
chrome.exe                   20020 Console                    1     75,248 K
chrome.exe                    5004 Console                    1     22,168 K
msedge.exe                   25332 Console                    1     19,580 K
tasklist.exe                 31980 Console                    1     12,464 K

C:\Users\yuvasri>dir
 Volume in drive C is Windows
 Volume Serial Number is DCAD-30DF

 Directory of C:\Users\yuvasri

30-04-2026  10:59    <DIR>          .
29-08-2025  00:14    <DIR>          ..
17-04-2026  09:31    <DIR>          .claude
30-04-2026  10:59               231 .claude.json
17-03-2026  15:34    <DIR>          .copilot
26-01-2026  21:21    <DIR>          .idlerc
29-04-2026  09:35    <DIR>          .vscode
20-04-2026  11:06    <DIR>          Antriofin for web
12-10-2025  18:37    <DIR>          Bharathwaj
29-08-2025  00:19    <DIR>          Contacts
18-03-2026  00:50    <DIR>          cover
06-01-2026  12:08    <DIR>          CrossDevice
28-03-2026  17:10    <DIR>          Desktop
10-11-2025  19:51    <DIR>          Documents
01-05-2026  20:57    <DIR>          Downloads
17-10-2025  22:14    <DIR>          Dribble
10-09-2025  10:15    <DIR>          env1
23-10-2025  10:54    <DIR>          exam
29-08-2025  00:19    <DIR>          Favorites
08-10-2025  20:30    <DIR>          igallery
29-08-2025  00:19    <DIR>          Links
07-02-2026  13:39               270 manage.py
03-10-2025  16:59    <DIR>          MathServer
07-09-2025  10:14    <DIR>          Music
24-09-2025  11:17    <DIR>          NearMe
26-08-2025  21:45    <DIR>          New folder
01-05-2026  18:27    <DIR>          OneDrive
12-02-2026  17:54    <DIR>          ORM
23-10-2025  10:25    <DIR>          practical
23-02-2026  10:55    <DIR>          PyCharmMiscProject
12-10-2025  20:45    <DIR>          restweb
29-08-2025  00:19    <DIR>          Saved Games
29-08-2025  00:19    <DIR>          Searches
15-10-2025  15:38    <DIR>          self growth of me
25-09-2025  13:56    <DIR>          simplewebserver
20-09-2025  09:24    <DIR>          slot
10-10-2025  14:26    <DIR>          softcompany
28-03-2026  17:04    <DIR>          Videos
28-08-2025  13:37    <DIR>          vscode for python
               2 File(s)            501 bytes
              37 Dir(s)  331,904,212,992 bytes free

C:\Users\yuvasri>chkdsk
Access Denied as you do not have sufficient privileges or
the disk may be locked by another process.
You have to invoke this utility running in elevated mode
and make sure the disk is unlocked.

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
System Boot Time:              30-04-2026, 10:14:25
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
Available Physical Memory:     2,172 MB
Virtual Memory: Max Size:      27,577 MB
Virtual Memory: Available:     8,938 MB
Virtual Memory: In Use:        18,639 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\LAPTOP-I5EN8JVF
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5082417
                               [02]: KB5054156
                               [03]: KB5083769
                               [04]: KB5088467
Network Card(s):               2 NIC(s) Installed.
                               [01]: Realtek RTL8852BE WiFi 6 802.11ax PCIe Adapter
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     10.129.146.23
                                     IP address(es)
                                     [01]: 10.129.146.162
                                     [02]: fe80::95c8:bca0:3ccf:930a
                                     [03]: 2401:4900:7b8e:70:a1d7:6c4:4a7d:e824
                                     [04]: 2401:4900:7b8e:70:a7c7:db47:52c2:86b6
                               [02]: Bluetooth Device (Personal Area Network)
                                     Connection Name: Bluetooth Network Connection
                                     Status:          Media disconnected
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
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\yuvasri>shutdown
Usage: shutdown [/i | /l | /s | /sg | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/soft] [/fw] [/f]
    [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]

    No args    Display help. This is the same as typing /?.
    /?         Display help. This is the same as not typing any options.
    /i         Display the graphical user interface (GUI).
               This must be the first option.
    /l         Log off. This cannot be used with /m or /d options.
    /s         Shutdown the computer.
    /sg        Shutdown the computer. On the next boot, if Automatic Restart Sign-On
               is enabled, automatically sign in and lock last interactive user.
               After sign in, restart any registered applications.
    /r         Full shutdown and restart the computer.
    /g         Full shutdown and restart the computer. After the system is rebooted,
               if Automatic Restart Sign-On is enabled, automatically sign in and
               lock last interactive user.
               After sign in, restart any registered applications.
    /a         Abort a system shutdown.
               This can only be used during the time-out period.
               Combine with /fw to clear any pending boots to firmware.
    /p         Turn off the local computer with no time-out or warning.
               Can be used with /d and /f options.
    /h         Hibernate the local computer.
               Can be used with the /f option.
    /hybrid    Performs a shutdown of the computer and prepares it for fast startup.
               Must be used with /s option.
    /fw        Combine with a shutdown option to cause the next boot to go to the
               firmware user interface.
    /e         Document the reason for an unexpected shutdown of a computer.
    /o         Go to the advanced boot options menu and restart the computer.
               Must be used with /r option.
    /m \\computer Specify the target computer.
    /t xxx     Set the time-out period before shutdown to xxx seconds.
               The valid range is 0-315360000 (10 years), with a default of 30.
               If the timeout period is greater than 0, the /f parameter is
               implied.
    /c "comment" Comment on the reason for the restart or shutdown.
               Maximum of 512 characters allowed.
    /f         Force running applications to close without forewarning users.
               The /f parameter is implied when a value greater than 0 is
               specified for the /t parameter.
    /d [p|u:]xx:yy  Provide the reason for the restart or shutdown.
               p indicates that the restart or shutdown is planned.
               u indicates that the reason is user defined.
               If neither p nor u is specified the restart or shutdown is
               unplanned.
               xx is the major reason number (positive integer less than 256).
               yy is the minor reason number (positive integer less than 65536).

Reasons on this computer:
(E = Expected U = Unexpected P = planned, C = customer defined)
Type    Major   Minor   Title

 U      0       0       Other (Unplanned)
E       0       0       Other (Unplanned)
E P     0       0       Other (Planned)
 U      0       5       Other Failure: System Unresponsive
E       1       1       Hardware: Maintenance (Unplanned)
E P     1       1       Hardware: Maintenance (Planned)
E       1       2       Hardware: Installation (Unplanned)
E P     1       2       Hardware: Installation (Planned)
E       2       2       Operating System: Recovery (Unplanned)
E P     2       2       Operating System: Recovery (Planned)
  P     2       3       Operating System: Upgrade (Planned)
E       2       4       Operating System: Reconfiguration (Unplanned)
E P     2       4       Operating System: Reconfiguration (Planned)
  P     2       16      Operating System: Service pack (Planned)
        2       17      Operating System: Hot fix (Unplanned)
  P     2       17      Operating System: Hot fix (Planned)
        2       18      Operating System: Security fix (Unplanned)
  P     2       18      Operating System: Security fix (Planned)
E       4       1       Application: Maintenance (Unplanned)
E P     4       1       Application: Maintenance (Planned)
E P     4       2       Application: Installation (Planned)
E       4       5       Application: Unresponsive
E       4       6       Application: Unstable
 U      5       15      System Failure: Stop error
 U      5       19      Security issue (Unplanned)
E       5       19      Security issue (Unplanned)
E P     5       19      Security issue (Planned)
E       5       20      Loss of network connectivity (Unplanned)
 U      6       11      Power Failure: Cord Unplugged
 U      6       12      Power Failure: Environment
  P     7       0       Legacy API shutdown

C:\Users\yuvasri>cleanmgr

C:\Users\yuvasri>cleanmgr

C:\Users\yuvasri>cleanmgr

## Result
Thus Execution of Network commands Performed 
