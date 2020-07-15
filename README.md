# PS3HENhouse v3.0.1

![PS3xploit logo](https://github.com/sheidhen/ps3henhouse/blob/master/public/ps3xploit-logo.png?raw=true)

## Compatible with 4.84, 4.85, and 4.86 HFW ONLY

> PS3HENhouse is an unauthorized way to self-host PS3HEN. Don't go harass the ps3xploit folk about it.

## What Is HEN:

**HEN** stands for **H**omebrew **EN**abler. It's a PS3 thing. I'm assuming you know what it is, otherwise this whole thing is not of any use to you.

## What is this, then?

PS3HENhouse is a way to self-host the **PS3HEN** exploit, for times when the official link is down.

## How do I use it?

Follow this tutorial by Coro:
[(NEW) Auto HEN Installer & OFFLINE Guide](https://www.psx-place.com/threads/new-auto-hen-installer-offline-guide.30400/)

When part 2 asks you to _start your webserver_, do this bit below:

```
npm i
npm run serve
```

Then, when your friendly HEN guide tells you to open the browser, use the address you see in your terminal (as below) as your destination:

```
✗ npm run serve
> ps3henhouse@3.0.1 serve ./ps3henhouse
> serve

INFO: Discovered configuration in `serve.json`

   ┌────────────────────────────────────────────────────┐
   │                                                    │
   │   Serving!                                         │
   │                                                    │
   │   - Local:            http://localhost:5000        │
   │   - On Your Network:  http://192.168.x.x:5000      │
   │                                                    │
   └────────────────────────────────────────────────────┘
```

Kill this process when done.

## @TODO

 - write better docs

## Random links

[PS3HEN @ GitHub](https://github.com/PS3Xploit/PS3HEN)
[PSX-PLACE:: [UPDATE-4.86] PS3HEN v3.0.1 - View latest changes to the PS3 Exploit for SuperSlims & nonCFW models](https://www.psx-place.com/threads/update-4-86-ps3hen-v3-0-1-view-latest-changes-to-the-ps3-exploit-for-superslims-noncfw-models.23955/)
[PSX-PLACE:: (NEW) Auto HEN Installer & OFFLINE Guide](https://www.psx-place.com/threads/new-auto-hen-installer-offline-guide.30400/)
