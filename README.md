# yet-another-darksword-campaign-targeting-cryptocurrency-wallets

# IOCs

Indicators of compromise accompanying the blog post:
**[Yet Another Darksword Campain Targeting Cryptocurrency Wallets](https://www.own.security/ressources/blog/yet-another-darksword-campaign-targeting-cryptocurrency-wallets)**

## Organization

IOCs are grouped by infrastructure cluster, one CSV file per cluster, in the `clusters/` directory:

| File | Cluster | Entries |
|---|---|---|
| `01_coruna_exploit_delivery_c2.csv` | Coruna exploit delivery C2 cluster | 102 domains |
| `02_154.13.7.145.csv` | 154.13.7.145 cluster | 101 domains |
| `03_appvip.cyou.csv` | appvip.cyou cluster | 19 domains |
| `04_crypto_wallet_guardian_webtitle.csv` | "Crypto wallet guardian" web title cluster | 88 FQDNs |
| `05_103.20.220.36_funnull.csv` | 103.20.220.36 ("FUNNULL") cluster | 182 FQDNs |

## Format

- Comma-separated, UTF-8, one header row.
- Dates are in ISO 8601 format (`YYYY-MM-DD`).
- Columns vary by cluster depending on the available data (e.g. `domain`, `fqdn`, `ip`, `asn`, `registrar`, `create_date`, `first_seen`, `last_seen`).
- Indicators are **not defanged**. Handle with care.

See the blog post for context, pivots and analysis behind each cluster.

## Author
[@fkn_apollo](https://x.com/fkn_apollo)
