    Ads              Advertisements, Banners, Push Notifications, Widgets  
    Adult            Porn  
    Apple            Bloat 
    Chat             Chat Dialog Popups and Widgets (Not in Ads)
    Cryptocurrency   Bitcoin, Ethereum, Mining, etc. (Not Malware)  
    Dating           Dating Sites  
    DNS              DNS Resolvers  
    Dynamic          Dynamic DNS  
    Fonts            Fonts  
    Free             Free Hosting
    Gambling         Casino, Gambling, Poker
    Junk             Personally untrusted software, extensions, search engines, etc  
    Malware          Malware, Hijackers, Phishing, PUPs, Redirectors, Remote Scammers
    Marketing        Marketing, Ebay Listing Tools, etc  
    Microsoft        Apps, Bing, Bloat, Tiles, etc  
    Remote           Domains used for remote sessions  
    Risk             Bad ISP/Bots/Spam, Keyloggers, Device Monitoring, GPS, etc  
    Scam             Fake freight, gift cards, pets, products, firearms, news, support, etc  
    Shock            Gore, Gross, Torture
    Top_Level        Top Level Domains. Sorted by continent, then by country
    Tracking         Analytics, Diagnostics, Location, Metrics, Public IP  
    Tunnels          VPNs & Proxies  
    Typo             Misspelled websites / Typosquatting  
    URL Shortener    URL Shorteners  
  
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some of the allowed domains in Filter ^

```diff
- Notice
  - Due to increasing scams, all generic remote support domains will be added to the Malware list.
```

## Notes
- **Overlap**: Categories like *Ads* and *Tracking* may contain domains that do both.
- **Risk**: Blocking *junk*, *Free*, *Marketing*, *Risk* will probably break stuff.
- **Typo**: Contains mostly dead domains. Avoid on low-end devices.
- **Wildcards**: Some domains may appear dead (`badsite.com`), but subdomain (`1.badsite.com`) may be active.
- **Prefixes**: `www.`, `mobile.`, and `m.` are removed.
- **Sources**: Lists are made from a custom script and manual additions.

## Maintenance
- The repository is occasionally compressed to reduce size, removing logs, diffs, and previous commits.
- Dead/parked domains are periodically removed.

## Contributing
- Open an issue with a category, domain, reason, and proof (if possible).
- I will not merge other lists.
- Junk is my personal list. If it breaks something, whitelist it. I won't modify it.
