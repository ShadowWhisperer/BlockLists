    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat / Push Notifications  
    Bitcoin          Bitcoin Miner & Related Sites  
    Bloat            Fonts, Domains not required for software to function  
    Chat             Live / Bot Chat Dialog Boxes  
    Dating           Dating Sites  
    Dynamic          Dynamic DNS:  DNS --> IP  
    Free             Free/Cheap Hosting & Blogs  
    Junk             Survey, Customer Junk, Personally Untrusted Antivirus, ISPs, Non USA Sites, etc  
    Malware          Malicious Sites, PUPs, Malware, Brower Hijackers, Phishing Sites  
    Marketing        Web Marketing / Ebay Listing Tools  
    Marketing-Email  Email Based Marketing  
    Microsoft        Apps, Bing, Tiles, Unknown  
    Pirate           Torrent / Magnet Sites, Trackers, Warez  
    Remote           Domains used to remotely control your stuff  
    Scam             Fake / Misleading Sites - Not directly malware  
    Suspicious       Found while searching other domains. Contains mixture of uncertain domains  
    Top_Level        Top Level Domains: Will block most non-traditional domains  
    Tracking         Analytics, Diagnostics, Location, Metrics, Puplic IP  
    Tunnels          VPNs & Proxies  *** NOT ALL ARE CHECKED ***  
    Typo             Typosquatting / Misspelling of websites. Custom script + domaincheckplugin.com/typo  
    Unknown          Site that have appeared in my logs  


Most of these domains are sorted by type. Some domains that are used as ad servers are also used for tracking. And the other way around.

I try to keep dead / parked domains / sinkholed domains out of these lists. I remove _www<span></span>._ _mobile._ _m._

These lists are all verified by me. Either by going to the domain or by using automated tools that I have written. These domains are a mix of domains I have found, and other users have compiled.

I manage a computer repair shop, and I am able to see which domains are being reached by the computers that come in.

_Free_, _Junk_, _Marketing*_, _Suspicious_, and _Unknown_ may/will break some websites.
  
  
**Create Block List**  
  while read -r Line || [[ -n "$Line" ]]; do  
  echo "0.0.0.0 $Line www<span></span>.$Line mobile.$Line m.$Line" >> /etc/block/$Name  
  done < /tmp/List
  
  
__**Useful Links**__  
[Norton Safeweb](https://safeweb.norton.com/)  
[Sucuri Site Check](https://sitecheck.sucuri.net/)  
[VirusTotal](https://www.virustotal.com/gui/home/url)  
  
[Typo Generator](http://domaincheckplugin.com/typo)
