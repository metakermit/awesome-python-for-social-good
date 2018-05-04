# Awesome Python for Social Good [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of examples & ideas of using Python for Social Good.

## Contents

- [Environment](#environment)
- [Internet](#internet)
- [Privacy](#privacy)
- [Free Press](#free-press)
- [Democracy](#democracy)
- [Politics](#politics)
- [Volunteering](#volunteering)

## Environment

- global warming data
  - [deleted data](https://www.theguardian.com/us-news/2017/may/14/donald-trump-climate-change-mentions-government-websites) – Trump’s administration [deleting public data on climate change from government websites
  - archivers
    * https://envirodatagov.org/
    * http://eotarchive.cdlib.org/2016.html
    * http://www.cdlib.org/
    * http://www.ppehlab.org/datarefuge
    * https://climatemirror.org/
  - Python scraping
    * Requests + BeautifulSoup
    * https://scrapy.org/
    * https://scrapinghub.com/
- the current rate of power consumption for cryptocurrency mining is a bit worrisome
  * Iceland, Denmark…
    * https://www.washingtonpost.com/news/worldviews/wp/2018/02/13/cryptocurrency-mining-in-iceland-is-using-so-much-energy-the-electricity-may-run-out/
    * https://www.theguardian.com/technology/2018/jan/17/bitcoin-electricity-usage-huge-climate-cryptocurrency
  * ⚡️ Call for action
    * is there a way to make such computation more green?
      * supply-demand balancing
      * negative energy prices
      * helping balance out volatility of wind turbines
    * can a proof of environment friendliness be encoded in the blockchain?

## Internet

- [recent DDoS attacks](https://threatpost.com/in-wake-of-biggest-ever-ddos-attack-experts-say-brace-for-more/130205/) – the "Mirai" botnet attack on DynDNS and the Memcached attack on GitHub
- [recent vulnerabilities](https://medium.com/threat-intel/bug-branding-heartbleed-14ef1a64047f) – Heartbleed, Shellshock, Meltdown, Spectre, oh my!
- make sure your servers are secure
  * don’t expose Memcached to the Internet!
  * [server](https://github.com/punkrockdev/server) – keep your software up to date. Unattended OS upgrades using Ansible
  * [PyMetasploit](https://github.com/allfro/pymetasploit) – a Python library for running Metasploit, the tool for pen-testing your sites
  * learn the basics of internet security
    * [hashlib](https://docs.python.org/3/library/hashlib.html) – hash passwords with scrypt
    * [Let’s encrypt](https://letsencrypt.org/) – use HTTPS
    * [cryptography.io](https://cryptography.io) – don’t roll your own crypto, use existing good implementations
- don’t let your users behave insecurely
  * [86% of passwords are terrible](https://www.troyhunt.com/86-of-passwords-are-terrible-and-other-statistics/) – people use `123456`, `password`, …
  * [Pwned Passwords v2](https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/) – elegant & safe API check
- maybe help keep an eye on the Internet
    * check those smart toasters exposed to the internet now & then
    * https://thehackernews.com/2016/02/hacking-wireless-router.html
    * https://www.forbes.com/sites/thomasbrewster/2015/10/01/vigilante-malware-makes-you-safer/#4771f3521fd5
    * _not the hero Gotham deserves…_

## Privacy

## Free Press

## Democracy

## Politics

## Volunteering

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Dražen Lučanin](https://metakermit.com) has waived all copyright and related or neighboring rights to this work.