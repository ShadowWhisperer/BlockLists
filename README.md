    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat  
    Bloat            Fonts, Surveys, Domains not required for software to function  
    Chat             Chat Dialog Popups  
    Cryptocurrency   Bitcoin, Ethereum, Mining, etc. (Not malware, but could be used by it)  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting, Free Blogs  
    Junk             Personally Untrusted Antivirus, Browser Extensions, Search Engines, etc  
    Malware          Malicious Sites, PUPs, Malware, Browser Hijackers, Phishing Sites  
    Marketing        Marketing, Ebay Listing Tools, etc  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Bloat, Tiles, etc  
    Remote           Domains used for remote sessions  
    Risk             Bad ISP/Bots/Spam, Keyloggers, Sites used by compromised devices
    Scam             Fake freight, gift cards, products, support, pet sales, firearms, news, etc    
    Shock            Gore, Gross, and Torture sites
    Top_Level        Top Level Domains. Sorted by Continent, then by country
    Tracking         Analytics, Diagnostics, Location, Metrics, Public IP  
    Tunnels          VPNs & Proxies  
    Typo             Misspelling of websites / Typosquatting  
    URL Shortener    URL Shorteners. Can be used to mask malicious domains
      
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains  
  

This repo was created: 2/14/2020.  https://api.github.com/repos/ShadowWhisperer/BlockLists  
The repo is compressed occasionally, to reduce the overall size. Logs, diff, etc. do not stay with the repo because of this.  
  
These lists are built using custom scripts, and manual additions. (All of my own)
<br />  
  
Some domains are used for both ads and tracking.  *Dating* may contain scam dating sites.  *Bloat*, *Free*, *Junk*, and *Marketing* will probably break stuff. *Typo* will have mostly dead domains. Not recommended to use on lower-end devices. If you're looking to merge my lists, I would advise you to skip *Typo*. You will get a lot of complaints of dead domains.  
<br />  

If you find sites that do not resolve an IP, it's probably a wildcard block. If _badsite.com_ is dead, _1.badsite.com_ is not. I remove dead/parked sites occasionally.  
<br />  

  
_www<span></span>._ _mobile._ _m._ prefixes are removed. They are added in the script below. This keeps the lists shorter.  
  
**Create Block List (Bash)**

    while read -r D || [[ -n "$D" ]]; do echo "0.0.0.0 $D www.$D mobile.$D m.$D" >> OUT; done < LIST  
<br />  
