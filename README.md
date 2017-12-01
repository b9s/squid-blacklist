# squid-blacklist
Stoplist of URL for Squid proxy server for more privacy and speed up browsing.
Block for ads, metrics, sexshops and etc


Usage on Squid.conf:

acl blacklist url_regex -i "/etc/squid/blacklist2"
http_access deny blacklist

