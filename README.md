# PiHole Blocklists

A set of blocklists for PiHole, based on APT reasearch output primarily.

Do not consider these to be concrete protection, of course! A lot of malware communicates using IP addresses rather than domain names, which renders PiHole ineffective against such threats. But this should help a little against the threats which *do* use domain names in their C2.

## Sources

| List | Source | Comment |
|---|---|---|
|`securielite-nk-apt.txt`|https://blog.google/threat-analysis-group/update-campaign-targeting-security-researchers/|North Korean state APT, targeting security researchers|
|`fireeye-icedid.txt`|https://www.fireeye.com/blog/threat-research/2021/02/melting-unc2198-icedid-to-ransomware-operations.html|ICEDID Ransomware.|
|`fireeye-dhl-woff-phishing.txt`|https://www.fireeye.com/blog/threat-research/2021/01/phishing-campaign-woff-obfuscation-telegram-communications.html|DHL phishing campaign using WOFF-based ciphers.|