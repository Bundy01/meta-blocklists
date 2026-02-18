# Meta Blocklists
**I'm taking over the excellent [facebook-extended.txt](https://github.com/lightswitch05/hosts/blob/master/docs/lists/facebook-extended.txt) hosts list after his repo is archived.**

## Contributions
* **In case you find a domain that is not listed in the `manual-domains` file**

You can add it to this file, which is sorted alphabetically. I'd search for valid sub-domains.

Command to sort the file:
```console
sort -u FILE -o manual-domains
```

* **If you find a valid sub-domain that is not blocked**

You can create the `manual-subdomains` file, if not already present and add it to this new file (format: xyz.example.com). It will be sorted alphabetically too.

* **Otherwise, if you're not familiar with `git` , you can also open an ISSUE**

## Example of Using Lists
| Blocklist | For Example |
|:----------|:------------|
| meta-adblock.txt | Pi-hole, Adblock Plus, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave, AdNauseam, Little Snitch Mini |
| meta-dnsmasq.txt | DNSMasq (v2.86 or newer), Diversion (v5 or newer) |
| meta-domains.txt | Blokada, Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| meta-hosts*.txt | AdAway, uMatrix, DNS66, NetGuard, Gas Mask|
| meta-rpz-wildcard.txt | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| meta-unbound.txt | Unbound |

## Support
I'm not asking you to buy me a coffee. But if you like this repo, give it a star 🌟️.
This will give it more visibility. Thanks!

## Special Thanks
Thank you @lightswitch05 for your work.

