# Hack_Pack_V1.0
<p align="center">
<img src="images.png" width="300" height="300" />   
</p>
## -->> Mega Combo of top selected hacking tools with description and working <<-- 

  * *Each tool is hand selected and verified as important tool for pentration testing and BugBounty.*
  * *Boom Lets get Started*


### (1) dnscan https://github.com/rbsec/dnscan
####   -Description  
        dnscan is a python wordlist-based DNS subdomain scanner.  
        The script will first try to perform a zone transfer using each of the target domain's nameservers.
####   -Usage   
        dnscan.py (-d <domain> | -l <list>)  
          
          
        
        
        
### (2) Knockpy https://github.com/guelfoweb/knock
####   -Description  
        Knockpy is a python3 tool designed to enumerate subdomains on a target domain through dictionary attack.
####   -Usage   
        $ knockpy domain.com
          
### (3) Sublist3r https://github.com/aboul3la/Sublist3r
####   -Description  
        Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT. It helps penetration testers and bug hunters collect and gather               subdomains for the domain they are targeting.
####   -Usage   
       To enumerate subdomains of specific domain and show only subdomains which have open ports 80 and 443 :
       python sublist3r.py -d example.com -p 80,443
       
NOTE- the output of the sublister needs to be passed from httpstatus.io to validate the results

### (4) massdns https://github.com/blechschmidt/massdns
####   -Description  
        MassDNS is a simple high-performance DNS stub resolver targeting those who seek to resolve a massive amount of domain names in the order of millions or           even billions. 
####   -Usage   
       $ ./bin/massdns -r lists/resolvers.txt -t AAAA domains.txt > results.txt  
       Load all your domains in domain.txt


### (5) nmap https://nmap.org
####   -Description    
         At a practical level, Nmap is used to provide detailed, real-time information on your networks, and on the devices connected to them.
####   -Usage   
       $nmap -A scanme.nmap.org
       
### (4) masscan https://github.com/robertdavidgraham/masscan
####   -Description  
        This is an Internet-scale port scanner. It can scan the entire Internet in under 5 minutes, transmitting 10 million packets per second, from a single              machine.Its usage (parameters, output) is similar to nmap, the most famous port scanner. When in doubt, try one of those features -- features that               support widespread scanning of many machines are supported, while in-depth scanning of single machines aren't.
####   -Usage    
        masscan -p80,8000-8100 10.0.0.0/8 2603:3001:2d00:da00::/112 --echo > xxx.conf
        
### (4) EyeWitness https://github.com/ChrisTruncer/EyeWitness
####   -Description  
        EyeWitness is designed to take screenshots of websites provide some server header info, and identify default credentials if known.
        Main key feature is about its addons and a html report file is created.
NOTE-   Aquatone could be better replacement for this.   

### (4) DirBuster https://sourceforge.net/projects/dirbuster/
####   -Description   
        DirBuster is a multi threaded java application designed to brute force directories and files names on web/application servers.
####   -Usage   
       A java Application hence easy to use .
       
NOTE   -Dirsearch might be a better replacement for this. A command line tool.

### (4) Dirsearch https://github.com/maurosoria/dirsearch
####   -Description   
        "dirsearch" is a mature command-line tool designed to brute force directories and files in webservers.
####   -Usage    
        python3 dirsearch.py -u http://XXXXX/ -w db/worldlist.txt


### (4) Gitrob https://github.com/michenriksen/gitrob
####   -Description 
        Gitrob is a command line tool which can help organizations and security professionals find sensitive information lingering in publicly available files on         GitHub. The tool will iterate over all public organization and member repositories and match filenames against a range of patterns for files that                 typically contain sensitive or dangerous information.
        Faced alots of issues while installing , use the beta release 
####   -Usage   
       gitrob [options] target [target2] ... [targetN]

### (4) sandcastle https://github.com/yasinS/sandcastle
####   -Description   
        A Python script for AWS S3 bucket enumeration, formerly known as bucketCrawler.The script takes a target's name as the stem argument (e.g. shopify) and           iterates through a file of bucket name permutations, such as the ones below:
####   -Usage
        sandcastle.py [-h] -t targetStem 
       
### (4) bucket_finder https://digi.ninja/projects/bucket_finder.php
####   -Description   
        This is a fairly simple tool to run, all it requires is a wordlist and it will go off and check each word to see if that bucket name exists in the                 Amazon's S3 system. Any that it finds it will check to see if the bucket is public, private or a redirect.
####   -Usage   
       ./bucket_finder.rb my_words
       
### (4) Wayback Machine https://web.archive.org
####   -Description   
        A browser extension which quickly checks to by pass 404 page that might have previously stored in the machine.
####   -Usage   
       add the browser extension.
       
bonus Dork- site: http://www.target.com filetype:txt  

### (4) waybackurls https://gist.github.com/mhmdiaa/adf6bff70142e5091792841d4b372050 
####   -Description   
        Waybackurls Fetch known URLs from the Wayback Machine for *.domain and output them on stdout. As wayback machine which stored urls of our target .                 Waybackurls r eturns as result a list of all the URLs that the Wayback Machine stored .
####   -Usage   
        cat domains.txt | waybackurls > urls
        
### (4) XRay https://github.com/evilsocket/xray
####   -Description   
        XRay is a tool for network OSINT gathering, its goal is to make some of the initial tasks of information gathering and network mapping automatic.
####   -Usage   
        xray -shodan-key YOUR_SHODAN_API_KEY -domain TARGET_DOMAIN


### (4) wfuzz https://github.com/xmendez/wfuzz/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       

### (4) Sn1per https://github.com/1N3/Sn1per/
####   -Description   
        
####   -Usage   
       






























patator https://github.com/lanjelot/patator

datasploit https://github.com/DataSploit/datasploit

hydra https://github.com/vanhauser-thc/thc-hydra

changeme https://github.com/ztgrace/changeme

MobSF https://github.com/MobSF/Mobile-Security-Framework-MobSF/ 

Apktool https://github.com/iBotPeaches/Apktool

dex2jar https://sourceforge.net/projects/dex2jar/

sqlmap http://sqlmap.org/

oxml_xxe https://github.com/BuffaloWill/oxml_xxe/

XXE Injector https://github.com/enjoiz/XXEinjector

The JSON Web Token Toolkit https://github.com/ticarpi/jwt_tool

ground-control https://github.com/jobertabma/ground-control

ssrfDetector https://github.com/JacobReynolds/ssrfDetector

LFISuit https://github.com/D35m0nd142/LFISuite

GitTools https://github.com/internetwache/GitTools

dvcs-ripper https://github.com/kost/dvcs-ripper

tko-subs https://github.com/anshumanbh/tko-subs

HostileSubBruteforcer https://github.com/nahamsec/HostileSubBruteforcer

Race the Web https://github.com/insp3ctre/race-the-web

ysoserial https://github.com/GoSecure/ysoserial

PHPGGC https://github.com/ambionics/phpggc

CORStest https://github.com/RUB-NDS/CORStest

retire-js https://github.com/RetireJS/retire.js

getsploit https://github.com/vulnersCom/getsploit

Findsploit https://github.com/1N3/Findsploit

bfac https://github.com/mazen160/bfac

WPScan https://wpscan.org/

CMSMap https://github.com/Dionach/CMSmap

Amass https://github.com/OWASP/Amass

exclude dirbuster and sniper Amass due 
