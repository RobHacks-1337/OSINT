# Some useful Tools:

Tools:

***exiftool / strings***
```
	> Reveals the metadata embedded in the image.
```
***nslookup***
```
	> just a basic DNS lookup utility.
	> Can use various record types to know additional information as well :-
		{A-IpV4, AAAA-Ipv6, MX-Mail Server, NS-Name Server, TXT-miscellaneous, CNAME-cannonical}.
```
***WHOIS***
 ```
	> Basic Domain Query Tool
	> Searches for domains registerd in whois directory [RFC 3912 database]
 ```
***gpg***
```
	> OpenPGP encryption and signing tool
	> Used to find the email address from public pgp key:
		1. Save public PGP key in .asc [ASCII-armored (text)] file
		2. Then use gpg --import xxxx.asc to get the info
```
