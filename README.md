# PiHole Blocklists

A set of blocklists for PiHole, based on APT reasearch output primarily.

Do not consider these to be concrete protection, of course! A lot of malware communicates using IP addresses rather than domain names, which renders PiHole ineffective against such threats. But this should help a little against the threats which *do* use domain names in their C2.

Also note that some of these may be out-of-date. If you're relying on any of these, especially for corporate use, ensure you check the dates of the source documents listed below, to determine if the list is recent enough for your purposes.

## Sources

| List | Source | Comment | Domains |
|---|---|---|---|
|`tag-securielite-nk-apt.txt`|https://blog.google/threat-analysis-group/update-campaign-targeting-security-researchers/|North Korean state APT, targeting security researchers|13|
|`fireeye-icedid.txt`|https://www.fireeye.com/blog/threat-research/2021/02/melting-unc2198-icedid-to-ransomware-operations.html|ICEDID Ransomware.|4|
|`fireeye-dhl-woff-phishing.txt`|https://www.fireeye.com/blog/threat-research/2021/01/phishing-campaign-woff-obfuscation-telegram-communications.html|DHL phishing campaign using WOFF-based ciphers.|46|
|`fireeye-unc1878.txt`|https://www.fireeye.com/blog/threat-research/2020/10/kegtap-and-singlemalt-with-a-ransomware-chaser.html|UNC1878 RYUK ransomware C2 domains|277|
|`fireeye-apt34.list`|https://www.fireeye.com/blog/threat-research/2017/12/targeted-attack-in-middle-east-by-apt34.html|Iran state APT|5| 
|`fireeye-apt33.txt`|https://www.fireeye.com/blog/threat-research/2017/09/apt33-insights-into-iranian-cyber-espionage.html|Iran state APT|15| 
|`fireeye-apt41.txt`|https://content.fireeye.com/apt-41/rpt-apt41/|China state APT|26| 
|`fireeye-apt28.txt`|https://www.fireeye.com/content/dam/fireeye-www/global/en/current-threats/pdfs/rpt-apt28.pdf|Russia state APT|26| 