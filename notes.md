All the tools and commands we used
                ["host","Host - Checks for existence of IPV6 address.","host",1],

                #2
                ["aspnet_config_err","ASP.Net Misconfiguration - Checks for ASP.Net Misconfiguration.","wget",1],

                #3
                ["wp_check","WordPress Checker - Checks for WordPress Installation.","wget",1],

                #4
                ["drp_check", "Drupal Checker - Checks for Drupal Installation.","wget",1],

                #5
                ["joom_check", "Joomla Checker - Checks for Joomla Installation.","wget",1],

                #6
                ["uniscan","Uniscan - Checks for robots.txt & sitemap.xml","uniscan",1],

                #7
                ["wafw00f","Wafw00f - Checks for Application Firewalls.","wafw00f",1],

                #8
                ["nmap","Nmap - Fast Scan [Only Few Port Checks]","nmap",1],

                #9
                ["theHarvester","The Harvester - Scans for emails using Google's passive search.","theHarvester",1],

                #10
                ["dnsrecon","DNSRecon - Attempts Multiple Zone Transfers on Nameservers.","dnsrecon",1],

                #11
                #["fierce","Fierce - Attempts Zone Transfer [No Brute Forcing]","fierce",1],

                #12
                ["dnswalk","DNSWalk - Attempts Zone Transfer.","dnswalk",1],

                #13
                ["whois","WHOis - Checks for Administrator's Contact Information.","whois",1],

                #14
                ["nmap_header","Nmap [XSS Filter Check] - Checks if XSS Protection Header is present.","nmap",1],

                #15
                ["nmap_sloris","Nmap [Slowloris DoS] - Checks for Slowloris Denial of Service Vulnerability.","nmap",1],

                #16
                ["sslyze_hbleed","SSLyze - Checks only for Heartbleed Vulnerability.","sslyze",1],

                #17
                ["nmap_hbleed","Nmap [Heartbleed] - Checks only for Heartbleed Vulnerability.","nmap",1],

                #18
                ["nmap_poodle","Nmap [POODLE] - Checks only for Poodle Vulnerability.","nmap",1],

                #19
                ["nmap_ccs","Nmap [OpenSSL CCS Injection] - Checks only for CCS Injection.","nmap",1],

                #20
                ["nmap_freak","Nmap [FREAK] - Checks only for FREAK Vulnerability.","nmap",1],

                #21
                ["nmap_logjam","Nmap [LOGJAM] - Checks for LOGJAM Vulnerability.","nmap",1],

                #22
                ["sslyze_ocsp","SSLyze - Checks for OCSP Stapling.","sslyze",1],

                #23
                ["sslyze_zlib","SSLyze - Checks for ZLib Deflate Compression.","sslyze",1],

                #24
                ["sslyze_reneg","SSLyze - Checks for Secure Renegotiation Support and Client Renegotiation.","sslyze",1],

                #25
                ["sslyze_resum","SSLyze - Checks for Session Resumption Support with [Session IDs/TLS Tickets].","sslyze",1],

                #26
                ["lbd","LBD - Checks for DNS/HTTP Load Balancers.","lbd",1],

                #27
                ["golismero_dns_malware","Golismero - Checks if the domain is spoofed or hijacked.","golismero",1],

                #28
                ["golismero_heartbleed","Golismero - Checks only for Heartbleed Vulnerability.","golismero",1],

                #29
                ["golismero_brute_url_predictables","Golismero - BruteForces for certain files on the Domain.","golismero",1],

                #30
                ["golismero_brute_directories","Golismero - BruteForces for certain directories on the Domain.","golismero",1],

                #31
                ["golismero_sqlmap","Golismero - SQLMap [Retrieves only the DB Banner]","golismero",1],

                #32
                ["dirb","DirB - Brutes the target for Open Directories.","dirb",1],

                #33
                ["xsser","XSSer - Checks for Cross-Site Scripting [XSS] Attacks.","xsser",1],

                #34
                ["golismero_ssl_scan","Golismero SSL Scans - Performs SSL related Scans.","golismero",1],

                #35
                ["golismero_zone_transfer","Golismero Zone Transfer - Attempts Zone Transfer.","golismero",1],

                #36
                ["golismero_nikto","Golismero Nikto Scans - Uses Nikto Plugin to detect vulnerabilities.","golismero",1],

                #37
                ["golismero_brute_subdomains","Golismero Subdomains Bruter - Brute Forces Subdomain Discovery.","golismero",1],

                #38
                ["dnsenum_zone_transfer","DNSEnum - Attempts Zone Transfer.","dnsenum",1],

                #39
                ["fierce_brute_subdomains","Fierce Subdomains Bruter - Brute Forces Subdomain Discovery.","fierce",1],

                #40
                ["dmitry_email","DMitry - Passively Harvests Emails from the Domain.","dmitry",1],

                #41
                ["dmitry_subdomains","DMitry - Passively Harvests Subdomains from the Domain.","dmitry",1],

                #42
                ["nmap_telnet","Nmap [TELNET] - Checks if TELNET service is running.","nmap",1],

                #43
                ["nmap_ftp","Nmap [FTP] - Checks if FTP service is running.","nmap",1],

                #44
                ["nmap_stuxnet","Nmap [STUXNET] - Checks if the host is affected by STUXNET Worm.","nmap",1],

                #45
                ["webdav","WebDAV - Checks if WEBDAV enabled on Home directory.","davtest",1],

                #46
                ["golismero_finger","Golismero - Does a fingerprint on the Domain.","golismero",1],

                #47
                ["uniscan_filebrute","Uniscan - Brutes for Filenames on the Domain.","uniscan",1],

                #48
                ["uniscan_dirbrute", "Uniscan - Brutes Directories on the Domain.","uniscan",1],

                #49
                ["uniscan_ministresser", "Uniscan - Stress Tests the Domain.","uniscan",1],

                #50
                ["uniscan_rfi","Uniscan - Checks for LFI, RFI and RCE.","uniscan",1],

                #51
                ["uniscan_xss","Uniscan - Checks for XSS, SQLi, BSQLi & Other Checks.","uniscan",1],

                #52
                ["nikto_xss","Nikto - Checks for Apache Expect XSS Header.","nikto",1],

                #53
                ["nikto_subrute","Nikto - Brutes Subdomains.","nikto",1],

                #54
                ["nikto_shellshock","Nikto - Checks for Shellshock Bug.","nikto",1],

                #55
                ["nikto_internalip","Nikto - Checks for Internal IP Leak.","nikto",1],

                #56
                ["nikto_putdel","Nikto - Checks for HTTP PUT DEL.","nikto",1],

                #57
                ["nikto_headers","Nikto - Checks the Domain Headers.","nikto",1],

                #58
                ["nikto_ms01070","Nikto - Checks for MS10-070 Vulnerability.","nikto",1],

                #59
                ["nikto_servermsgs","Nikto - Checks for Server Issues.","nikto",1],

                #60
                ["nikto_outdated","Nikto - Checks if Server is Outdated.","nikto",1],

                #61
                ["nikto_httpoptions","Nikto - Checks for HTTP Options on the Domain.","nikto",1],

                #62
                ["nikto_cgi","Nikto - Enumerates CGI Directories.","nikto",1],

                #63
                ["nikto_ssl","Nikto - Performs SSL Checks.","nikto",1],

                #64
                ["nikto_sitefiles","Nikto - Checks for any interesting files on the Domain.","nikto",1],

                #65
                ["nikto_paths","Nikto - Checks for Injectable Paths.","nikto",1],

                #66
                ["dnsmap_brute","DNSMap - Brutes Subdomains.","dnsmap",1],

                #67
                ["nmap_sqlserver","Nmap - Checks for MS-SQL Server DB","nmap",1],

                #68
                ["nmap_mysql", "Nmap - Checks for MySQL DB","nmap",1],

                #69
                ["nmap_oracle", "Nmap - Checks for ORACLE DB","nmap",1],

                #70
                ["nmap_rdp_udp","Nmap - Checks for Remote Desktop Service over UDP","nmap",1],

                #71
                ["nmap_rdp_tcp","Nmap - Checks for Remote Desktop Service over TCP","nmap",1],

                #72
                ["nmap_full_ps_tcp","Nmap - Performs a Full TCP Port Scan","nmap",1],

                #73
                ["nmap_full_ps_udp","Nmap - Performs a Full UDP Port Scan","nmap",1],

                #74
                ["nmap_snmp","Nmap - Checks for SNMP Service","nmap",1],

                #75
                ["aspnet_elmah_axd","Checks for ASP.net Elmah Logger","wget",1],

                #76
                ["nmap_tcp_smb","Checks for SMB Service over TCP","nmap",1],

                #77
                ["nmap_udp_smb","Checks for SMB Service over UDP","nmap",1],

                #78
                ["wapiti","Wapiti - Checks for SQLi, RCE, XSS and Other Vulnerabilities","wapiti",1],

                #79
                ["nmap_iis","Nmap - Checks for IIS WebDAV","nmap",1],

                #80
                ["whatweb","WhatWeb - Checks for X-XSS Protection Header","whatweb",1],

                #81
                ["amass","AMass - Brutes Domain for Subdomains","amass",1]