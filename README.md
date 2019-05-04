# livelock-app

Demonstrates the occurence of a livelock ('after you, no after you, no after you ...).

See the dump folder for a capture of thed thread dump.


## Taking Dump

```
jps -lV

jstack <PID> > threaddump.txt