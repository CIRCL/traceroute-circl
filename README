# traceroute-circl

traceroute-circl is an extended traceroute to support
the activities of CSIRT (or CERT) operators. Usually
CSIRT team have to handle incidents based on IP addresses
received.

## Features

- Display abuse and contact for each hop
- Can highligh specific country to match CSIRT's constituency
- Output RBL entries for each hop
- Show ASN origin from RIPE RIS and origin.asn.cymru.com sources

## Usage

        perl traceroute-circl --ip 1.2.3.4
        perl traceroute-circl --rbl ipbl.zeustracker.abuse.ch --ip 1.2.3.4
        perl traceroute-circl --country LU --ip www.circl.lu 

        traceroute-circl v0.1
        usage: traceroute-circl [options] 
        options                                                         
        -d, --debug     Debug mode                                      
        -i, --ip        IP address to lookup                            
        -r, --rbl       RBL domain to lookup                            
        -c, --country   Country ISO code to highlight (!!) in the output
        -h, --help      This help message                               
            --man       Display documentation                           


## Dependencies

- Perl
- Perl Module Getopt::Compact
- Perl Module Net::Whois::RIS
- Perl Module IP::Country::Fast
- Perl Module Net::Abuse::Utils
- and existing "traceroute"/"traceroute-nanog" on your operating system

## Authors

Copyright (C) 2010 Alexandre Dulaunoy
Copyright (C) 2010 CIRCL Computer Incident Response Center Luxembourg (smile gie)

