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

## Special Thanks
Thank you @lightswitch05 for your work.
