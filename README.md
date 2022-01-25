# RedBlueNotes

![red](https://user-images.githubusercontent.com/9626439/99510946-ef79e900-2987-11eb-9aa8-1443670a8bb3.jpg)

Personal notes and collection of useful links. 

Collection in early stage - more details will be added (URL/Description).

## Approach
* [assume breach?](https://twitter.com/reybango/status/1308608385298898944)

## Lab
* [designing-the-adversary-simulation-lab/](https://www.mdsec.co.uk/2020/04/designing-the-adversary-simulation-lab/)

## .NET ETW 
* https://www.mdsec.co.uk/2020/03/hiding-your-net-etw/ (bypass by _xpn_)
* https://github.com/zacbrown/PowerKrabsEtw
* https://github.com/zacbrown/hiddentreasure-etw-demo

## Windows syscalls
* https://outflank.nl/blog/2019/06/19/red-team-tactics-combining-direct-system-calls-and-srdi-to-bypass-av-edr/
* https://github.com/jthuraisamy/SysWhispers
* https://jhalon.github.io/utilizing-syscalls-in-csharp-1/
* https://jhalon.github.io/utilizing-syscalls-in-csharp-2/
* https://www.solomonsklash.io/syscalls-for-shellcode-injection.html
* https://github.com/frkngksl/Celeborn
* https://github.com/m0rv4i/Syscalls-Extractor

## (API) (un)hook
* [Defeat Bitdefender total security using windows API unhooking to perform process injection](https://shells.systems/defeat-bitdefender-total-security-using-windows-api-unhooking-to-perform-process-injection/)
* [Part 1: Fs Minifilter Hooking](https://aviadshamriz.medium.com/part-1-fs-minifilter-hooking-7e743b042a9d)
* [Windows API Hooking](https://rcvalle.com/blog/2020/09/16/rust-lang-exploit-mitigations/)

## EDR telemetry
* [TelemetrySourcerer](https://github.com/jthuraisamy/TelemetrySourcerer)

## Build offensive tools 
* [OffensivePipeline](https://github.com/Aetsu/OffensivePipeline)

## Infrastrcuture
* [Multi-Stage Offensive Operations with Mythic](https://blog.kyleavery.com/posts/multi-stage-mythic/)

## Evasion
* [Blue team - EDR evolution](https://www.optiv.com/insights/source-zero/blog/endpoint-detection-and-response-how-hackers-have-evolved)
* [Nice webinar - understanding-modern-edr-tools](https://www.netspi.com/webinars/understanding-modern-edr-tools-thank-you/)
* [Lets Create An EDR… And Bypass It! Part 1](https://ethicalchaos.dev/2020/05/27/lets-create-an-edr-and-bypass-it-part-1/)
* [Lets Create An EDR… And Bypass It! Part 2](https://ethicalchaos.dev/2020/06/14/lets-create-an-edr-and-bypass-it-part-2/)
* [A Guide to Reversing and Evading EDRs: Part 1 Introduction](http://jackson-t.ca/edr-reversing-evading-01.html)
* [A Guide to Reversing and Evading EDRs: Part 2 Sensor reconnaisssance](http://jackson-t.ca/edr-reversing-evading-02.html)
* [A Guide to Reversing and Evading EDRs: Part 3 Diverting EDR telemetry to private infrastracture](http://jackson-t.ca/edr-reversing-evading-03.html)
* [Alaris](https://github.com/cribdragg3r/Alaris)
* [ScareCrow](https://github.com/optiv/ScareCrow)
* [Self deleting exe](https://www.catch22.net/tuts/win32/self-deleting-executables#)
* [Defeating Antivirus Real-time Protection From The Inside](https://breakdev.org/defeating-antivirus-real-time-protection-from-the-inside/)
* [Duping AV with handles](https://skelsec.medium.com/duping-av-with-handles-537ef985eb03)
* [Adventures in Dynamic Evasion](https://posts.specterops.io/adventures-in-dynamic-evasion-1fe0bac57aa)
  * [Companion PoC for the "Adventures in Dynamic Evasion" blog post](https://github.com/matterpreter/SHAPESHIFTER) 
* [Click your shortcut and… you got pwned.](https://redteamer.tips/click-your-shortcut-and-you-got-pwned/) 
* [Evade EDR with Shellcode Injection and gain persistence using Registry Run Keys](https://infosecwriteups.com/evade-avs-edr-with-shellcode-injection-159dde4dba1a)
* [Understanding and bypassing AMSI](https://x64sec.sh/understanding-and-bypassing-amsi/)
* [Masking Malicious Memory Artifacts – Part III: Bypassing Defensive Scanners](https://www.forrest-orr.net/post/masking-malicious-memory-artifacts-part-iii-bypassing-defensive-scanners)
* [smaller-c-payloads-on-windows](https://www.solomonsklash.io/smaller-c-payloads-on-windows.html)
* [in-memory-shellcode-decoding-to-evade-avs](https://shells.systems/in-memory-shellcode-decoding-to-evade-avs/)
* [MDSec Bypassing Image Load Kernel Callbacks](https://www.mdsec.co.uk/2021/06/bypassing-image-load-kernel-callbacks/)
* [EDR bypass via signed driver EDRSandblast](https://github.com/wavestone-cdt/EDRSandblast)

## Cloud
* [XPN - Azure AD Connect for Red Teamers](https://blog.xpnsec.com/azuread-connect-for-redteam/)
* [Making Clouds Rain :: Remote Code Execution in Microsoft Office 365](https://srcincite.io/blog/2021/01/12/making-clouds-rain-rce-in-office-365.html)
* [List of Azure CDN IP Addresses](https://github.com/Gelob/azure-cdn-ips)
* [AWS IAM explained for Red and Blue teams](https://infosecwriteups.com/aws-iam-explained-for-red-and-blue-teams-2dda8b20fbf7)
* [Exploiting AWS IAM permissions for total cloud compromise: a real world example (part 1/2)](https://infosecwriteups.com/exploiting-fine-grained-aws-iam-permissions-for-total-cloud-compromise-a-real-world-example-part-5a2f3de4be08)
* [Exploiting fine-grained AWS IAM permissions for total cloud compromise: a real world example (part 2/2)](https://infosecwriteups.com/exploiting-aws-iam-permissions-for-total-cloud-compromise-a-real-world-example-part-2-2-f27e4b57454e)

## Lateral movement
* [lateral-movement-using-dcom-objects](https://www.scorpiones.io/articles/lateral-movement-using-dcom-objects)

# DLLs
* https://itm4n.github.io/windows-dll-hijacking-clarified/
* https://github.com/monoxgas/Koppeling (DLL hijacking)
* https://redteaming.co.uk/2020/07/12/dll-proxy-loading-your-favorite-c-implant/ (DLL proxy loading)
* [Full DLL Unhooking with C++](https://www.ired.team/offensive-security/defense-evasion/how-to-unhook-a-dll-using-c++)

## Injections
* https://sevrosecurity.com/2020/04/08/process-injection-part-1-createremotethread/
* https://sevrosecurity.com/2020/04/13/process-injection-part-2-queueuserapc/

## Situational Awareness
* https://ired.team/offensive-security/enumeration-and-discovery/windows-event-ids-for-situational-awareness

## Phishing
* [Post exploitation creds](https://medium.com/@shantanukhande/post-exploitation-creds-5a8de8676792)
* [Adversary phishing characteristics](https://blog.sannemaasakkers.com/adversary-phishing-characteristics.html)
* [Check the phishing server / landing page response](https://httpstatus.io/)
* [Security check of your URL ](https://sitecheck.sucuri.net/)
* [Check your phishing e-mail quality](https://www.mail-tester.com/)
* [Recipe for a successful phishing campaign (part 1/2)](https://medium.com/bugbountywriteup/recipe-for-a-successful-phishing-campaign-part-1-2-dc23d927ec55)
  * setup SPF, DKIM, PTR, MX and general approach
* [Recipe for a successful phishing campaign (part 2/2)](https://medium.com/bugbountywriteup/recipe-for-a-successful-phishing-campaign-part-2-2-68552806dcba)
  * setup DNS, gophishg, general tips for better campaign
* [Building resilient phishing campaign infrastructure](https://godlikesecurity.com/index.php/tag/red-team/)
* [email spoofing](https://github.com/chenjj/espoofer)
* [docker,terradorm,ansible automation](https://github.com/ralphte/build_a_phish)
* [Internal phishing](https://github.com/Yaxser/SharpPhish)
* [Password protected Excel phishing](https://s3cur3th1ssh1t.github.io/Phish-password-protected-Excel-files/)
* [Gophish notification](https://github.com/dunderhay/gophish-notifications)
* [Gophish notification via webhooks](https://github.com/t94j0/gophish-notifier)

### Phishing platforms
* [sendgrid](http://sendgrid.com/)
  * useful service but honestly, You need Pro pain plan to be lucky not to be on a spamlist 
* [mailgun](https://app.mailgun.com/)
  * haven't had any problem
* [Amazon AWS SES](https://aws.amazon.com/ses/)

## Download and execute

* [Download via Defender](https://twitter.com/mohammadaskar2/status/1301263551638761477)
![Defender download](https://pbs.twimg.com/media/Eg8ESSWWAAACTGo?format=jpg&name=large)
* (You can use C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2008.9-0\MpCmdRun.exe -url <url> -path <local-path> to download your file using Windows defender itself.)
  
## Reports and management
* [Manage Red Team domain](https://posts.specterops.io/being-a-good-domain-shepherd-part-2-5e8597c3fe63)
* [Domain Shepherd](https://github.com/GhostManager/Shepherd)

## SSH 
* If you are always looking through your ssh conf files for a specific host entry, this simple bash function might be just what you need. 

```
function getssh() {
  awk "/$1/,/^$/" < ~/.ssh/include/*
}
```

![SSH configs](https://pbs.twimg.com/media/EgW_CXzXsAEsh0r?format=png&name=small)

## Tools
* [Weaponry](https://github.com/jeffjbowie/Weaponry)
  * A collection of offensive code used for red team engagements.                                    
* [Mr-Un1k0d3r awesome repo](https://github.com/Mr-Un1k0d3r)  
* [PowerShellArmoury](https://github.com/cfalta/PowerShellArmoury) 
* [RedTeamTools](https://github.com/lengjibo/RedTeamTools)     
* [inceptor](https://github.com/klezVirus/inceptor)   
* [mgeeky awesome repo](https://github.com/mgeeky/Penetration-Testing-Tools/tree/master/red-teaming)                                    

## HW
* [Making the Perfect Red Team Dropbox (Part 1)](https://sensepost.com/blog/2020/making-the-perfect-red-team-dropbox-part-1/)
* [Making the Perfect Red Team Dropbox (Part 2)](https://sensepost.com/blog/2020/making-the-perfect-red-team-dropbox-part-2/)
