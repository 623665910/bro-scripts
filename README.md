# bro-scripts

This repository contains the [Bro](http://www.bro.org) scripts I've written.

- Example output of `syslog-outbound.bro` script:

```shell
$ zcat 2013-*/notice* | grep Outbound | head -1
1377595970.788206     YI9hmdEIE46       31.2.42.8 10269   63.43.24.59  514     -       -       -       udp     SYSLOG::Detected_Outbound_Message       Syslog message destined to non-local networks    -       31.2.42.8 63.43.24.59  514
```

- Example output of `ipmi.bro` script:

```shell
$ zcat 2013-09-*/notice* | grep IPMI | head -1
1378045519.036048     C1lfYJ1t1ilC0NTOuf  IPMI::Port_Detected     Host 19.190.23.6 sent traffic to UDP port 623.  ...
```

