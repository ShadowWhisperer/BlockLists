    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat  
    Bloat            Fonts, Surveys, Domains not required for software to function  
    Chat             Chat Dialog Popups  
    Cryptocurrency   Bitcoin, Ethereum, Mining, etc. (Not malware, but could be used by it)  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting, Free Blogs  
    Gambling         Gambling sites    
    Junk             Personally Untrusted Antivirus, Browser Extensions, Search Engines, etc  
    Malware          Malicious Sites, PUPs, Malware, Browser Hijackers, Phishing Sites  
    Marketing        Marketing, Ebay Listing Tools, etc  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Bloat, Tiles, etc  
    Remote           Domains used for remote sessions  
    Risk             Worst ISP Bots/Spam, Keyloggers, URL Shortener, Used by compromised devices
    Scam             Fake freight, gift cards, products, support, pet sales, firearms, news, etc    
    Shock            Gore, Gross, Torture, Race/Gender
    Top_Level        Top Level Domains. Sorted by Continent, then by country
    Tracking         Analytics, Diagnostics, Location, Metrics, Public IP  
    Tunnels          VPNs & Proxies  
    Typo             Misspelling of websites / Typosquatting  
      
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains  
  
A lot of lists are a bunch of other users' lists combined into one. These lists all built by me, either by going to the site, IP address, or custom scripts. I have multiple systems running dnsmasq, with ~40 people using them; including a computer repair center. A lot of my data comes from those logs. Others are from honeypots (*Cowrie*), and top 1 million lists. I try to keep dead, parked, and sinkholed domains out of these lists.

Websites that contain malware (example: malvertising) are not in these lists. They are not blocked or allowed. The malware within the sites are blocked.  

Some domains are used for both ads and tracking.  Dating list may contain scam dating sites.  

*Free*, *Junk*, and *Marketing* may break some sites.  
  
_www<span></span>._ _mobile._ _m._ prefixes are removed. They are added in the script below. This keeps the lists shorter.  
<br />  

**Create Block List (Bash)**

    while read -r D || [[ -n "$D" ]]; do echo "0.0.0.0 $D www.$D mobile.$D m.$D" >> OUT; done < LIST  
<br />  

**Useful Links**  
[Norton Safeweb](https://safeweb.norton.com/)  
[Sucuri Site Check](https://sitecheck.sucuri.net/)  
[VirusTotal](https://www.virustotal.com/gui/home/url)  
  
[SSL Lookup](https://mxtoolbox.com/HTTPSLookup.aspx)  
[Whois](https://www.whois.com/whois/)  
  
[Spamhaus Statistics](https://www.spamhaus.org/statistics/countries/)  

[Typo Generator](http://domaincheckplugin.com/typo)  *Use "Add Extension to Typos", or the generator will make invalid TLDs  
