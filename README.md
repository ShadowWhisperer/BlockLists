    Ads              Advertisements, Banners, Widgets & Push Notifications  
    Adult            Porn / 18+ Content  
    Apple            Bloat  
    Bloat            Domains not required for software to function  
    Chat             Chat Dialog Popups  
    Cryptocurrency   Bitcoin, Ethereum, Mining, etc. (Not Malware)  
    Dating           Dating Sites  
    DNS              DNS Resolvers  
    Dynamic          Dynamic DNS
    Fonts            Fonts  
    Free             Free/Cheap Hosting, Free Blogs  
    Gambling         Casino, Gambling, Poker
    Junk             Personally untrusted software, browser extensions, search engines, etc  
    Malware          Malicious Sites, PUPs, Malware, Browser Hijackers, Phishing  
    Marketing        Marketing, Ebay Listing Tools, etc  
    Microsoft        Apps, Bing, Bloat, Tiles, etc  
    Remote           Domains used for remote sessions  
    Risk             Bad ISP/Bots/Spam, Keyloggers, Device Monitoring, GPS, etc  
    Scam             Fake freight, gift cards, products, support, pets, firearms, news, etc    
    Shock            Gore, Gross, and Torture sites
    Top_Level        Top Level Domains. Sorted by continent, then by country
    Tracking         Analytics, Diagnostics, Location, Metrics, Public IP  
    Tunnels          VPNs & Proxies  
    Typo             Misspelled websites / Typosquatting  
    URL Shortener    URL Shorteners. Can be used to mask malicious domains
      
    Filter           Used by my parse script to show me what has not been blocked
    Whitelist        Reasons for some allowed domains in Filter ^

```diff
- Notice
  Due to increasing scams, all generic remote support domains will be added to the Malware list.
```

## Usage Notes
- **Overlap**: Categories like *Ads* and *Tracking* may overlap.
- **Risk**: Blocking *Bloat*, *Free*, or *Marketing*, *Risk* may break stuff.
- **Typo**: Contains mostly dead domains. Avoid on low-end devices or when merging with your lists.
- **Wildcard Blocks**: Some domains may appear dead (e.g. `badsite.com`), but subdomains (e.g. `1.badsite.com`) may remain active.
- **Prefixes**: `www.`, `mobile.`, and `m.` are removed.
- **Sources**: Lists are made from a custom script and manual additions.

## Maintenance
- The repository is occasionally compressed to reduce size, removing logs, diffs, and previous commits.
- Dead or parked domains are periodically removed.

## Contributing
- Open an issue with category, domain, reason, and proof (if possible).
- I will not merge other lists.

## Formats
[HOSTS](https://github.com/ShadowWhisperer/BlockLists/tree/master/Hosts) -   0.0.0.0 domain.com  
[Lists](https://github.com/ShadowWhisperer/BlockLists/tree/master/Lists) - domain.com  *also contains wildcards  
[RAW](https://github.com/ShadowWhisperer/BlockLists/tree/master/RAW) - Same as Lists, but without comment lines  
  
[Whitelists](https://github.com/ShadowWhisperer/BlockLists/tree/master/Whitelists)
