# orbisnmpd
Cross compile of snmpd for Orbi (ARMv7) so you can monitor these devices with NSM tools

## Script to install from command line
```
cd / && \$
curl -kL https://github.com/ctixsystems/orbisnmpd/raw/main/snmpd.tgz | \$
tar xvfz - &&\$
/tmp/snmpd/snmpd -c /tmp/snmpd/snmpd.conf$
```
