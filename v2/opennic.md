# opennic

Resolvers from the [OpenNIC](https://www.opennic.org/) project.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'opennic']
    url = 'http://download.dnscrypt.info/resolvers-list/v2/opennic.md'
    minisign_key = 'RWQf6LRCGA9i53mlYecO4IzT51TGPpvWucNSCh1CBM0QTaLn73Y7GFO3'
    cache_file = 'opennic.md'
    format = 'v2'

This list was last updated on 2018-01-31

--

## fvz-anyone
Fusl's public primary OpenNIC Tier2 Anycast DNS Resolver
sdns://AQYAAAAAAAAAEzE4NS4xMjEuMTc3LjE3Nzo0NDMgGmrQoytMWmGmldFTZw1pqxaQP57D9_ZPE-U1oxiyKKUdMi5kbnNjcnlwdC1jZXJ0LmRuc3JlYy5tZW8ud3M


## fvz-anytwo
Fusl's public secondary OpenNIC Tier2 Anycast DNS Resolver
sdns://AQYAAAAAAAAAEzE2OS4yMzkuMjAyLjIwMjo0NDMgGmrQoytMWmGmldFTZw1pqxaQP57D9_ZPE-U1oxiyKKUdMi5kbnNjcnlwdC1jZXJ0LmRuc3JlYy5tZW8ud3M


## opennic-famicoman
OpenNIC DNS server with DNSCrypt support
sdns://AQYAAAAAAAAAEzE0Ni4xODUuMTc2LjM2OjUzNTMguI9IYFUXNpaj0r_g7MdhdRmP4BLhAbT-hpwenEw15082Mi5kbnNjcnlwdC1jZXJ0Lm9wZW5uaWMucGVlcjMuZmFtaWNvbWFuLnBoaWxseW1lc2gubmV0


## opennic-tumabox
Public DNS server operated by TumaBox.org
sdns://AQYAAAAAAAAAEjEzMC4yNTUuNzMuOTA6NTM1MyDVkXsRajUxFMI4qpmm6wwofPdoBUGsXb-ooCOeIoxbBg0yLnR1bWFib3gub3Jn


## opennic-tumabox-ipv6
Public DNS server operated by TumaBox.org
sdns://AQYAAAAAAAAAG1syYTAyOmUwMDpmZmZkOjEzOTo6OV06NTM1MyDVkXsRajUxFMI4qpmm6wwofPdoBUGsXb-ooCOeIoxbBg0yLnR1bWFib3gub3Jn