# tcpretrans

## description 
A tool to trace TCP retransmission
Wrote with perl.
This tool is derived from the tool perf-tools wrote by Brendan Gregg.
In order to make it easy to use, I did some modification.
Currently this tool could run on kernel >= 2.6.32.

## usage     
-h      # help message
-l      # trace TCP tail loss probes
-s      # print stack traces
-a      # live trace.

Requires: 
root permission

