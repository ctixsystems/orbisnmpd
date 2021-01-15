# orbisnmpd
Cross compile of snmpd for Orbi (ARMv7) so you can monitor these devices with NSM tools

## Script to install from command line
```
curl https://github.com/ctixsystems/orbisnmpd/raw/main/snmpd.tgz > /tmp/snmpd.tgz
cd / && tar xvfz /tmp/snmpd.tgz
/tmp/snmpd/snmpd -c /tmp/snmpd/snmpd.conf
```
