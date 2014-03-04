Self-Surveillance 101
=====================

Collecting IP addresses to physically map my internet. Work in progress.

`logstash-grok.conf` takes tcpdump output and stores it as a csv file. The idea is I take that csv data, traceroute all the IPs that aren't my local machine, then geocode the traceroute IPs. 

This may or may not actually work. 