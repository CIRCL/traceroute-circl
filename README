# traceroute-circl

traceroute-circl is an extended traceroute to support
the activities of CSIRT (or CERT) operators. Usually
CSIRT team have to handle incidents based on IP addresses
received.

## Features

- Display abuse and contact for each hop
- Display CIRCL BGP Ranking services (experimental)
- Can highligh specific country to match CSIRT's constituency
- Output RBL entries for each hop
- Output Google Maps traceroute (e.g. [a sample output](http://www.foo.be/traceroute-circl/test.html) )
- Show ASN origin from RIPE RIS and origin.asn.cymru.com sources

## Usage

        perl traceroute-circl --ip 1.2.3.4
        perl traceroute-circl --rbl ipbl.zeustracker.abuse.ch --ip 1.2.3.4
        perl traceroute-circl --country LU --ip www.circl.lu 
        perl traceroute-circl -i australia.gov.au -m out.js
        perl traceroute-circl -i www.w3c.org -o"-I -v"

        traceroute-circl v0.3
        usage: traceroute-circl [options] 
        options                                                             
        -d, --debug         Debug mode                                      
        -i, --ip            IP address to lookup                            
        -r, --rbl           RBL domain to lookup                            
        -b, --bgpranking    Output CIRCL BGP Ranking for each ASN
        -o, --addoptions    Additional option to traceroute
        -c, --country       Country ISO code to highlight (!!) in the output
        -f, --fullcountry   Display full country name                       
        -m, --geomap        Output file for the google map                  
        -h, --help          This help message                               
            --man           Display documentation

## Dependencies

- Perl
- Perl Module Getopt::Compact
- Perl Module Net::Whois::RIS
- Perl Module IP::Country::Fast
- Perl Module Net::Abuse::Utils
- Perl Module Locale::Country
- Perl Module LWP::Simple (used for Google Maps country lookup)
- Perl Module JSON (used for Google Maps country lookup)
- and an existing "traceroute"/"traceroute-nanog" on your operating system

## Authors

Copyright (C) 2010-2011 Alexandre Dulaunoy

Copyright (C) 2010-2011 CIRCL Computer Incident Response Center Luxembourg (smile gie)

