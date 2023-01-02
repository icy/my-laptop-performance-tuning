## Description

As an engineer I need to tune my laptop to run at its best performance. Why? The answer is why not. 

## Specification

My laptop is pretty old. It's at least 7 years old. 
(I bought it from the 2nd market.)
Its memory capacity is 8GB. And cpu? 
It's a `Intel(R) Core(TM) i5-4210U CPU @ 1.70GHz` (2 cores x 2 threads)?
This is just enough for daiyl web surfing... until it isn't.

## Firefox

### Config

Most of the time I can't read/view two tabs at the same time, 
and my eyes wouldn't be faster than any cpu unit. 
When I slow down firefox I still see the same results. 
It's interesting that the defaults settings are very high 
and really make firefox hang on my laptop.

* dom.ipc.plugins.processLaunchTimeoutSecs=1
* dom.ipc.processCount=1
* dom.ipc.processCount.webIsolated=1
* dom.ipc.processCount.webLargeAllocation=1
* dom.ipc.processPrelaunch.fission.number=1
* avascript.options.concurrent_multiprocess_gcs.cpu_divisor=1

Note: It's said on some threads that Google's browser doesn't 
have any option to reduce the number of cores they are on. 
It may be wrong but only would I use such browser for some p***n site,
so not a big deal...

### Addons

The world has changed. Web owner don't want to waste their money and they force
web browsers (aka their clients) to use more and more resources. Some web owners
don't serve if you don't have javascript, the cpu&memory killer.

So let make that behavior default.

* NoScript
* Cookie Autodelete
* AdBlocker Ultimate
* uBlock Origin
* Ghostery

Note: I have AdGuard AdBlocker on firefox mobile version
