######################
#### # James Washington
#### # Network Engineer II
#### # 2018/06/19
######################

This is a simple script that will search various databses for advertised routes from an ASN you specify.
Currently I have configured it to query RADB, ARIN, APNIC, AFRINIC, LACNIC and RIPE.

To install
1. Log into the bash capable server you're installing it in
2. git clone https://github.com/tsali/asn_routes
3. cd into the asn_routes directroy
4. chmod +x asn
5. use from within the asn_routes directory (IE ./asn or bash asn,) or copy to /bin or /usr/bin as necessary

For the copy/paste inclined:                                                                                      

```
git clone https://github.com/tsali/asn_routes.git && cd asn_routes && chmod +x asn
```
