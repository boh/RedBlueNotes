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
[Post exploitation creds](https://medium.com/@shantanukhande/post-exploitation-creds-5a8de8676792)

## SSH 
* If you are always looking through your ssh conf files for a specific host entry, this simple bash function might be just what you need. 

```
function getssh() {
  awk "/$1/,/^$/" < ~/.ssh/include/*
}
```

![SSH configs](https://pbs.twimg.com/media/EgW_CXzXsAEsh0r?format=png&name=small)
