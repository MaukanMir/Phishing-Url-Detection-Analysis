# Phishing URL Detection

## About this file

#### This dataset consists in ~2.5M samples of URLs labeled as legitimate or phishing, taken from the main phishing URL repositories (PhishTank, Phishing.Database, OpenPhish-Community) and URL ranking sites (Cisco Umbrella Popularity List, The Majestic Million). It also contains 15 of the most relevant attributes in phishing detection:

- url	URL string
- source	Source of the URL (phishing URLs or URL ranking databases)
- label	Category of URL, either phishing or legitimate
- url_length	URL length in characters
- starts_with_ip	Is the base URL an IP address?
- url_entropy	URL/hostname entropy
- has_punycode	Does the URL contain at least one punycode character?
- digit_letter_ratio	Digit-letter character ratio in URL
- dot_count	Count of occurrences of dot (.) inside URL
- at_count	Count of occurrences of dot (@) inside URL
- dash_count	Count of occurrences of dot (-) inside URL
- tld_count	Does the subdirectory in the URL contain top-level domains?
- domain_has_digits	Does the domain (base URL) contain digits?
- subdomain_count	Count of subdomains featured in the base URL
- nan_char_entropy	Character entropy of non-alphanumeric characters inside the URL
- has_internal_links	Does the URL subdirectory contain links?
- whois_data**	Domain WHOIS record
- domain_age_days	Domain age in days, according to extracted WHOIS record