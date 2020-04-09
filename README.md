    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat / Push Notifications  
    Bitcoin          Bitcoin Miner & Related Sites  
    Bloat            Fonts, Domains not required for software to function  
    Chat             Live / Bot Chat Dialog Boxes  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting & Blogs  
    Junk             Survey, Junk, Personally Untrusted Antivirus, ISPs (Spam/Botnets), Non USA Sites, etc  
    Malware          Malicious Sites, PUPs, Malware, Brower Hijackers, Phishing Sites  
    Marketing        Web Marketing / Ebay Listing Tools  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Bloat, Tiles, Unknown  
    Pirate           Torrent / Magnet Sites, Torrent Trackers, Warez  
    Remote           Domains used to remotely control your stuff  
    Scam             Fake / Misleading Sites - Not malware  
    Suspicious       Contains mixture of uncertain domains (Ads, Trackers, Malware)  
    Top_Level        Top Level Domains: Will block most non-traditional domains  
    Tracking         Analytics, Diagnostics, Location, Metrics, Puplic IP  
    Tunnels          VPNs & Proxies
    Typo             Typosquatting / Misspelling of websites.  
    Unknown          Similar to Suspicious, but is more organized.  
  
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains  

Most of these domains are sorted by type. Some domains that are used as ad servers are also used for tracking, and vice versa.  

I try to keep dead / parked domains / sinkholed domains out of these lists. I remove _www<span></span>._ _mobile._ _m._  

These lists are all verified by me. Either by going to the domain or by using automated tools that I have written. These domains are a mix of domains I have found, and other users have compiled.  
  
  
_Free_, _Junk_, _Marketing*_, _Suspicious_, and _Unknown_ may/will break some websites.
  
  
**Create Block List**  
  while read -r Line || [[ -n "$Line" ]]; do  
  echo "0.0.0.0 $Line www<span></span>.$Line mobile.$Line m.$Line" >> OUTPUT
  done < INPUT_LIST
  
  
__**Useful Links**__  
[Norton Safeweb](https://safeweb.norton.com/)  
[Sucuri Site Check](https://sitecheck.sucuri.net/)  
[VirusTotal](https://www.virustotal.com/gui/home/url)  
  
[Typo Generator](http://domaincheckplugin.com/typo)
