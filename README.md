## Description

As an engineer I need to tune my laptop to run at its best performance. Why? The answer is why not. 

## Specification

My laptop is pretty old. It's at least 7 years old. 
(I bought it from the 2nd market.)
Its memory capacity is 8GB. And cpu? 
It's a `Intel(R) Core(TM) i5-4210U CPU @ 1.70GHz` (2 cores x 2 threads)?
This is just enough for daiyl web surfing... until it isn't.

## Firefox

Most of the time I can't read/view two tabs at the same time, 
and my eyes wouldn't be faster than any cpu unit. 
When I slow down firefox and still see the same results. 
It's interesting that the defaults settings are very high 
and really make firefox hang on my laptop.

* dom.ipc.plugins.processLaunchTimeoutSecs=1
* dom.ipc.processCount=1
* dom.ipc.processCount.webIsolated=1
* dom.ipc.processCount.webLargeAllocation=1
* dom.ipc.processPrelaunch.fission.number=1
* avascript.options.concurrent_multiprocess_gcs.cpu_divisor=1
