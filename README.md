# Nachos in Java

Original code is found in [CS 377: Operating Systems - Gettings Started with Nachos](http://lass.cs.umass.edu/~shenoy/courses/fall12/discussions/nachos/)


## How to build by own

```bash
$ wget http://lass.cs.umass.edu/~shenoy/courses/fall12/discussions/nachos/nachos-umass.tar.gz
$ tar xzvf nachos-umass.tar.gz 
$ cd nachos/proj1 
$ make 
$ ../bin/nachos 
```

NOTE: Don't change directory name, `nachos`! If you do, `make` doesn't work.

## How to build Nachos in this repo

```bash
$ git clone <this repo uri>
$ cd <this repo>
$ cd nachos
$ cd proj1
$ make 
$ ../bin/nachos 
```

Then you will get the following output

```
nachos 5.0j initializing... config interrupt timer user-check grader
*** thread 0 looped 0 times
*** thread 1 looped 0 times
*** thread 0 looped 1 times
*** thread 1 looped 1 times
*** thread 0 looped 2 times
*** thread 1 looped 2 times
*** thread 0 looped 3 times
*** thread 1 looped 3 times
*** thread 0 looped 4 times
*** thread 1 looped 4 times
Machine halting!

Ticks: total 2130, kernel 2130, user 0
Disk I/O: reads 0, writes 0
Console I/O: reads 0, writes 0
Paging: page faults 0, TLB misses 0
Network I/O: received 0, sent 0

```