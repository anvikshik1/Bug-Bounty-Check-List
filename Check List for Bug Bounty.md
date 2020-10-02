 # Recon Mind Map For Bug Bounty/Penetration Testing
 

**Information gathering:**

_Content Discovery_
  - [ ] ASN
     - IP Block/Subnet
       - [ ] [bgp.he.net](https://bgp.he.net/country)
       - [ ] [whois.arin.net](https://whois.arin.net/ui/)
       - [ ] [apps.db.ripe.net](https://apps.db.ripe.net/db-web-ui/query)
       - [ ] [ultratool.com](https://www.ultratools.com/tools/asnInfo)
       - [ ] [shodan.io](https://www.shodan.io/)
       - [ ] [dnsgoodies](http://dnsgoodies.com/)
       
     - Acquisition
       - [ ] [crunchbase.com](https://www.crunchbase.com/search/acquisition)
       - [ ] [viewdns.info](https://viewdns.info/reversewhois/ " First do whois, take the register email then perform reverse whois 'muni-adm@ics.muni.cz'")
       - [ ] [whoisxmlapi.com](https://tools.whoisxmlapi.com/reverse-whois-search)
       
 - [ ] Subdomain
     - Verticle domain corelation
     
       - [ ] [chaos.projectdiscovery.io](https://chaos.projectdiscovery.io/#/ "Single subdomains")
       - [ ] [Sublist3r](https://github.com/aboul3la/Sublist3r "Single subdomains")
       - [ ] [Amass](https://github.com/OWASP/Amass "Single subdomains")
       - [ ] [Aquatone](https://github.com/michenriksen/aquatone "Single subdomains")
       - [ ] [Knockpy](https://github.com/guelfoweb/knock "Single subdomains")
       - [ ] [Subfinder](https://github.com/projectdiscovery/subfinder "Multiple subdomains 'bruteforce subdomain+wordlist'")
       
     - Horizontal domain correlation
     
       - [ ] [Naive approach](/ "google.com, youtube.com, gmail.com" )
       - [ ] [bgpview.io](https://bgpview.io/search/google "Dedicated IP range, ASNs, IPv4") 
       - [ ] [reversewhois.domaintools.com](https://reversewhois.domaintools.com/)
       
_Certificate transparency_ 
  
  - [ ] [crt.sh](https://crt.sh/)
  - [ ] [developers.facebook.com](https://developers.facebook.com/tools/ct/search/)
  - [ ] [transparencyreport.google.com](https://transparencyreport.google.com/)
  
_JS Enumeration_  
   - [ ] [JSparser](https://github.com/nahamsec/JSParser)
   - [ ] [LinkFinder](https://github.com/GerbenJavado/LinkFinder)
   - [ ] [relative-url-extractor](https://github.com/jobertabma/relative-url-extractor)
   - [ ] [JS-Scan](https://github.com/zseano/JS-Scan)
   - [ ] [getJS](https://github.com/003random/getJS) 
   - [ ] [InputScanner](https://github.com/zseano/InputScanner)
 
_DNS Enumeration_ 
   - [ ] [syborg](https://github.com/MilindPurswani/Syborg)
   - [ ] [dnsrecon](https://github.com/darkoperator/dnsrecon)
   - [ ] [dnsgen](https://github.com/ProjectAnte/dnsgen "Automate dnsgen+masscan")
   
_WayBack Enumaretion_  
   - [ ] [Paramspider](https://github.com/devanshbatham/ParamSpider)
   - [ ] [waybachurl](https://github.com/tomnomnom/waybackurls)
   - [ ] [archive.org](https://archive.org/web/)
   - [ ] [waybackunifier](https://github.com/mhmdiaa/waybackunifier)
   - [ ] [parameth](https://github.com/maK-/parameth)
   - [ ] [waybackSqliScanner](https://github.com/ghostlulzhacks/waybackSqliScanner)
   - [ ] [gau](https://github.com/lc/gau)
   - [ ] [Arjun](https://github.com/s0md3v/Arjun)
   
_Supports_   
   - [ ] [gf](https://github.com/tomnomnom/gf)
   - [ ] [httprobe](https://github.com/tomnomnom/httprobe)
   - [ ] [nuclei](https://github.com/projectdiscovery/nuclei)
   - [ ] [shuffledns](https://github.com/projectdiscovery/shuffledns)
   - [ ] [meg](https://github.com/tomnomnom/meg)
   - [ ] [tojson](https://github.com/malijs/tojson)
   - [ ] [Interlace](https://github.com/codingo/Interlace)
   - [ ] [httpx](https://github.com/projectdiscovery/httpx)
   
_Subdomain Takeover_   
   - [ ] [can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz)
   - [ ] [SubOver](https://github.com/Ice3man543/SubOver)
   - [ ] [subjack](https://github.com/haccer/subjack)
   - [ ] [takeover](https://github.com/m4ll0k/takeover)
   - [ ] [subzy](https://github.com/LukaSikic/subzy)
   - [ ] [HostileSubBruteforcer](https://github.com/nahamsec/HostileSubBruteforcer)
   
_Fuzzing_  
   - [ ] [ffuf](https://github.com/ffuf/ffuf)
   - [ ] [wfuzz](https://github.com/xmendez/wfuzz)
   - [ ] [gobuster](https://github.com/OJ/gobuster)
   - [ ] [dirsearch](https://github.com/maurosoria/dirsearch)
   
_Port Scan_   
   - [ ] [nmap](https://github.com/nmap/nmap)
   - [ ] [masscan](https://github.com/robertdavidgraham/masscan)
   - [ ] [naabu](https://github.com/projectdiscovery/naabu)
   
_WAF Identification_

   - [ ] [wafw00f](https://github.com/EnableSecurity/wafw00f)
   - [ ] [nmap nse script](https://github.com/nmap/nmap/blob/master/scripts/http-waf-detect.nse)
   
_Wordlist/Payload_   
   - [ ] [content Discovery all.txt](https://gist.github.com/jhaddix/b80ea67d85c13206125806f0828f4d10)
   - [ ] [jhaddix all.txt](https://gist.github.com/jhaddix/f64c97d0863a78454e44c2f7119c2a6a)
   - [ ] [SecLists](https://github.com/danielmiessler/SecLists)
   - [ ] [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
   - [ ] [fuzzdb](https://github.com/fuzzdb-project/fuzzdb)
   - [ ] [many more...](https://github.com/foospidy/payloads)
   
_CMS Identification_
   - [ ] [wappalyzer](https://www.wappalyzer.com/lookup/)
   - [ ] [netcraft](https://www.netcraft.com/search/?q=google.com)
   - [ ] [whatweb](https://github.com/urbanadventurer/WhatWeb)
   - [ ] [retire.js](https://retirejs.github.io/retire.js/)
   - [ ] [builwith](https://github.com/ecrmnn/builtwith)
   
_Visual recon_   
   - [ ] [aqatone](https://github.com/michenriksen/aquatone)
   - [ ] [gowitness](https://github.com/sensepost/gowitness)
   - [ ] [webscreenshot](https://github.com/maaaaz/webscreenshot)
   - [ ] [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)
   
_Github recon_   
   - [ ] [gitrob](https://github.com/michenriksen/gitrob)
   - [ ] [git-hound](https://github.com/tillson/git-hound)
   - [ ] [shhgit](https://github.com/eth0izzle/shhgit)
   - [ ] [truffleHog](https://github.com/dxa4481/truffleHog)
   - [ ] [git-all-secrets](https://github.com/anshumanbh/git-all-secrets)
   - [ ] [gitGraber](https://github.com/hisxo/gitGraber)
   - [ ] [gihub manual dorking](https://raw.githubusercontent.com/anvikshik1/Bug-Bounty-Check-List/master/payload/gihub-manual-dork)
     
   
_Web vulnerability scanner tools_   
 
 **SSRF**
   - [ ] [nip.io](https://nip.io/)
   - [ ] [burp Collaborator ](https://gist.github.com/Isopach/00515b5f7ef7be230ff76c6092df0137)
   - [ ] [SSRFmap](https://github.com/swisskyrepo/SSRFmap)
   
 **CORS**  
   - [ ] [CORScanner](https://github.com/chenjj/CORScanner)
   - [ ] [Corsy](https://github.com/s0md3v/Corsy)
   - [ ] [Gf-Patterns](https://github.com/1ndianl33t/Gf-Patterns)
 
 **CSRF**  
   - [ ] [Blazy](https://github.com/s0md3v/Blazy)
   - [ ] [Bolt](https://github.com/s0md3v/Bolt) 
   - [ ] [XSRFProbe](https://github.com/0xInfection/XSRFProbe)
   
**XSS**   
   - [ ] [xsscrapy](https://github.com/DanMcInerney/xsscrapy)
   - [ ] [XSStrike](https://github.com/s0md3v/XSStrike)
   - [ ] [XSS Gf-Patterns](https://github.com/1ndianl33t/Gf-Patterns)
   - [ ] [xss wayback hunt](https://web.archive.org/web/*/google.com/*)
   
**Command Injection**   
   - [ ] [commix](https://github.com/commixproject/commix)
   - [ ] [open redirection + gf pattern](/ "")
   
**Open Redirect**   
   - [ ] [Open-Redirection-Scanner](https://github.com/KendoClaw1/Open-Redirection-Scanner)
   - [ ] [ORtester](https://github.com/Leonmugen/ORtester)
   - [ ] [open redirection + gf pattern](/ "")
   
