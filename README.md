# ARIN Org IPs
Query the ARIN REST API for a point-of-contact (POC) handle, and generate a list of CIDRs associated with that POC.

https://www.arin.net/resources/registry/whois/rws/api/

## Install
```
go get github.com/shaggy245/arin
```

## Usage
```
$ arin <poc-handle>
```

### Example
```
$ arin GODAD
["45.40.128.0/18","173.201.0.0/16","97.74.0.0/16","2603::/20","2607:F208::/32","160.153.0.0/16","166.62.0.0/17","184.168.0.0/16","192.186.192.0/18","72.167.0.0/16","192.169.128.0/17","198.12.128.0/17","198.71.128.0/17","208.109.0.0/16","216.69.128.0/18","23.229.128.0/17","64.202.160.0/19","68.178.128.0/17","50.62.0.0/15","107.180.0.0/17","104.238.64.0/18","132.148.0.0/16","148.72.0.0/16","2604:BC80::/32","50.30.32.0/20","104.244.168.0/21","162.211.120.0/21","162.254.200.0/21","173.224.112.0/20","192.155.96.0/20","199.189.84.0/22","199.217.112.0/21","207.38.80.0/20","209.126.96.0/19","209.239.112.0/20","2605:DE00::/32","69.64.32.0/19","64.97.0.0/16","64.96.128.0/17"]
```
