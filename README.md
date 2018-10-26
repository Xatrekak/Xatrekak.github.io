## Xatrekak's Code Repo

This pages **_should_** contain links to all of my code projects. These projects are usually initiated to solve a current problem, or address workflow issues. Because of this the code usually contains no comments (I will try to get better about this) and is no longer maintained once it works. However, if any one files an issue against the I have no issues making changes or merging code.

Also, a warning that I am very much a Network Engineer, **NOT** a Software Engineer. Any code found here comes with no warranties or promises that it wont immediately brick your computer. 

<br/>
<br/>

### [Lab Loader](https://xatrekak.github.io/lab-loader/)

>This is a quick GUI app that I threw together to solve some work flow issues I had while stuying for my CCIE. Uses python to make and mount a disk image containing bootup files for the lab routers. Currently this method only works for the vIOS images and only on Linux.

>At some point I will be adding Windows support via WSL (it requres GNU MTools). I will also be adding support for the CSR1000v which should have native windows support.

<br/>
<br/>

### [Multi-Threaded Ping Script](https://xatrekak.github.io/Multithreaded-Ping-Script)
>A simple bash script that reads IP addresses from a file "IPLIST.txt". Every IP address spawns a bash sub-process so it is entirly concurrent and very very fast. It has no resouce monitoring built in so if you pass too many IP address it will bog down.

> Results are exported to IPRESULTS.csv as $IP is up/down.

<br/>
<br/>

### [Multi-Threaded TCP Socket test Script](https://xatrekak.github.io/TCP-Socket-Test---Multi-Threaded)
>This is exactly the same as the ping test but it uses Linux kernal socket to test reachability to port 22 on TCP
>It will tell you that the IP address is up if it receives any response other than a timeout or address unreachable.

<br/>
<br/>

### [Cisco Call Manager Interface - Excel VBA](https://xatrekak.github.io/CUCM-API-GUI-Interface/)

>This is an excel VBA macro using a Form and hiding the excel sheet to emulate a GUI Program. I know this seems silly but it makes importing a code base into a secure system very easy as it has no outside dependencies at all. Also, since it is "just" an Excel sheet it doesn't need to go though a software approval process. 

>This is in a working state but has fallen to the way side as priorites have been shifted at work. Interfacing with the CUCM presents a ton of oppertunites to improve NOC works flows and VoIP availbilties, so I will pick this back up once I have time.

<br/>
<br/>
