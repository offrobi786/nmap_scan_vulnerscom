# nmap scan vulnerscom script

## plan to make on bash
Install nmap, download vulners script, scans and sends result on email

## description
Script runs nmap with vulnerscom script and send results on email, ispired by Flan scan. You need installed tar, git, nmap, nmap-scripts, mailutils, xsltproc and file scan.ips containing list of IP addresses, in working directory. Tested on Debian 9.

To run use `./scan.sh` as root, no parameters needed.
