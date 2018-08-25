# Awesome Python for Social Good [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of examples & ideas of using Python for Social Good.

This list is based on [my talk](https://speakerdeck.com/metakermit/python-for-social-good)
at PyDays Vienna 2018 and extended with new content over time. Contributions of new ideas and technical examples are very welcome. 🙂

## Contents

- [Environment](#environment)
- [Poverty](#poverty)
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
  * more power than Iceland, Denmark…
    * [cryptocurrency mining in Iceland is using so much energy the electricity may run out](https://www.washingtonpost.com/news/worldviews/wp/2018/02/13/cryptocurrency-mining-in-iceland-is-using-so-much-energy-the-electricity-may-run-out/)
    * [Bitcoin electricity usage](https://www.theguardian.com/technology/2018/jan/17/bitcoin-electricity-usage-huge-climate-cryptocurrency)
  * ⚡️ Call for action
    * is there a way to make such computation more green?
      * supply-demand balancing
      * negative energy prices
      * helping balance out volatility of wind turbines
    * can a proof of environment friendliness be encoded in the blockchain?

## Poverty

- Costa Rican household poverty level prediction using machine learning – [part1](https://towardsdatascience.com/a-data-science-for-good-machine-learning-project-walk-through-in-python-part-one-1977dd701dbc), [part2](https://towardsdatascience.com/a-data-science-for-good-machine-learning-project-walk-through-in-python-part-two-2773bd52daf0) & [the Kaggle competition](https://www.kaggle.com/c/costa-rican-household-poverty-prediction)

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
    * [white-hat hackers upgrading routers](https://thehackernews.com/2016/02/hacking-wireless-router.html)
    * [vigilante malware makes you safer](https://www.forbes.com/sites/thomasbrewster/2015/10/01/vigilante-malware-makes-you-safer/#4771f3521fd5)
    * _not the hero Gotham deserves…_

## Privacy

* [Snowden](https://en.wikipedia.org/wiki/Edward_Snowden) – revealed government surveillance programs (June 2013)
* ⚡️ Call for action
  * [Signal](https://signal.org/) – great e2e encrypted chat app, open source & needs UX help
  * [Mailpile](https://github.com/mailpile/Mailpile) – web-based email client w/ PGP in Python

## Free Press

- Fake news
- Attacks on journalists
- ⚡️ Call for action
  * help fact-checking sites
    * https://www.snopes.com/
    * http://www.politifact.com/
    * http://fivethirtyeight.com/
    * start something like this in your own community
  * Be wary of the possibility of tampering with information
  * TensorFlow detect fake news – Jupyter notebooks & datasets on Kaggle
    * [Kaggle fake news competition](https://www.kaggle.com/c/fake-news)
    * [Kaggle datasets related to "fake news"](https://www.kaggle.com/datasets?sortBy=relevance&search=fake+news)

## Democracy

* Facebook + Cambridge Analytics + trolls + fake news = impact elections
* [voting machines in Germany hacked](https://edition.cnn.com/2017/09/07/europe/germany-hackers-election-software/index.html) (7.9.2017.) – by white hat hackers this time
* [Cyber attack Estonia](https://www.theguardian.com/technology/2017/dec/02/fake-news-botnets-how-russia-weaponised-the-web-cyber-attack-estonia) – outright "cyber warfare"
* ⚡️ Call for action
  * help find software vulnerabilities
  * identify trolls / bots on social networks
    * TensorFlow
    * https://www.kaggle.com/vikasg/russian-troll-tweets

## Politics

* Analyse the data
  * open data
  * scrape it!
* Code for America / Europe / …
  * civic hacktivism
  * help your village/town/country make a better service for something
* help politicians you support
* subvert politicians you don’t 👹
  * [Trump2Cash](https://github.com/maxbbraun/trump2cash) – a stock trading bot powered by Trump tweets
  * [Trump2Cash blog post](https://medium.com/@maxbraun/this-machine-turns-trump-tweets-into-planned-parenthood-donations-4ece8301e722#.yovbh4qc1/)

## Volunteering

* helping the economically disadvantaged
* helping the misrepresented
* other forms of helping your community
* ⚡️ Call for action
  * both local & remote
    * http://www.refugeescode.at/
    * https://www.freecodecamp.org/nonprofits/
  * help teach others
    * [Python is the No. 1 language in education](https://cacm.acm.org/blogs/blog-cacm/176450-python-is-now-the-most-popular-introductory-teaching-language-at-top-u-s-universities/fulltext)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Dražen Lučanin](https://metakermit.com) has waived all copyright and related or neighboring rights to this work.
