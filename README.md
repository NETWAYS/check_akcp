# check\_akcp

This plugin recieves the data from akcp devices. It can check the thresholds of the connected probes.

## Usage

    check_akcp.pl -h
        
    check_akcp.pl --man
       
    check_akcp.pl -H <host> -P <Port> [-w <warning>] [-c <critical>]

Options:

```
-h Display this helpmessage.

-H The hostname or ipaddress of the akcp device.

-C The snmp community of the akcp device.

-P The port where the probe is connected to.

-w The warning threshold.

-c The critical threshold.

--man Displays the complete perldoc manpage.
```
