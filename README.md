# threatcrowd-puller
This script is used in order to pull information about an IP address for potentially known bad files and links from threatcrowd.

You can put in multiple IPs and receive only output based on hits, this also appends the IP at the end of the hit to better identify what IP it was ascociated with.

# Requirements:
Python3

# imports:
bs4, requests, json, re, sys, urllib3



# Usage:
python threatcrowd.py 103.133.108.72 81.22.45.62 192.168.2.56 141.98.81.52 61.177.172.32 218.92.0.31 185.143.221.29 92.118.37.26 104.206.128.23 185.200.118.18 112.85.42.16 185.176.27.16 68.183.83.16 139.220.192.14 178.62.42.14 185.137.233.14 103.114.107.12 103.89.91.12 187.115.165.12 178.128.214.11

https://www.threatcrowd.org/domain.php?domain=cirkus.se ['178.62.42.14']



python threatcrowd.py 74.82.47.13

https://www.threatcrowd.org/domain.php?domain=scan-12b.shadowserver.org ['74.82.47.13']
