# Blocklists for PiHole

When I update the Gravity (list of blocked domains) I get the error message

```
  [i] Target: raw.githubusercontent.com (hosts)
  [✗] Status: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts ()
  [✗] List download failed: using previously cached list
```

It happens due [IP addresses in list](https://discourse.pi-hole.net/t/list-download-failed-no-cached-list-available/23698/2).

This repo is created to add the rules I use and then will be used by PiHole.

## Next steps

* [ ] Create an script to pull files/repos and clean up for PiHole
* [ ] Put the script in a VPS to pull each 24hs and update this repo
