    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat
    Bitcoin          Bitcoin domains (Not directly malware)
    Bloat            Fonts, Surveys, Domains not required for software to function  
    Chat             Chat Dialog Popups  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting, Free Blogs  
    Junk             Personally Untrusted Antivirus, Browser Extensions, Search Engines, etc  
    Malware          Malicious Sites, PUPs, Malware, Browser Hijackers, Phishing Sites  
    Marketing        Marketing, Ebay Listing Tools, etc  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Bloat, Tiles, etc  
    Remote           Domains used for remote sessions  
    Risk             Worst ISP Bots/Spam, Keyloggers, URL Shortener, Used by compromised devices
    Scam             Fake freight, gift cards, products, support, pets sales, news, etc    
    Shock            Gore, Gross, Torture, Race/Gender Superiority  
    Top_Level        Top Level Domains. Sorted by Continent, then by country
    Tracking         Analytics, Diagnostics, Location, Metrics, Puplic IP  
    Tunnels          VPNs & Proxies  
    Typo             Misspelling of websites / Typosquatting  
      
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains  
  
Domains are sorted by category.  These are all verified by me.  I try to keep dead, parked, and sinkholed domains out of these lists. Some domains are used for both ads and tracking.  Dating list may contain scam dating sites.
  
_www<span></span>._ _mobile._ _m._ prefixes are removed. They are added in the script below. This keeps the lists shorter, and ensures the domain is fully blocked.  
  
_Free_, _Junk_, and _Marketing*_ may break some sites.
<br />  
<br />  
**Create Block List**  (Bash)  

    while read -r D || [[ -n "$D" ]]; do echo "0.0.0.0 $D www.$D mobile.$D m.$D" >> OUT; done < LIST  
<br />  

**Useful Links**  
[Norton Safeweb](https://safeweb.norton.com/)  
[Sucuri Site Check](https://sitecheck.sucuri.net/)  
[VirusTotal](https://www.virustotal.com/gui/home/url)  
  
[SSL Lookup](https://www.ultratools.com/tools/sslExam)  
[Whois](https://www.whois.com/whois/)  
  
[Spamhaus Statistics](https://www.spamhaus.org/statistics/countries/)  

[Typo Generator](http://domaincheckplugin.com/typo)  *Use "Add Extension to Typos", or the generator will make invalid TLDs  
