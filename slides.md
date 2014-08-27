class: center, middle

# FreeBSD is dying in Taiwan

Li-Wen Hsu &lt; lwhsu@FreeBSD.org &gt;

---
# Agenda

* What is FreeBSD
* How the FreeBSD project works
* The FreeBSD in Taiwan
* How to join FreeBSD project

---
# 197X
  * Unix &amp; Berkeley Software Distribution

# 1993
  * **Nate Williams**, **Rod Grimes**, and **Jordan Hubbard** came together to turn their 386BSD patchkit into something greater. **David Greenman** gave their combined efforts a name.

# 11 December, 1993
  * FreeBSD gets its name

---

```
To: interim@bsd.coe.montana.edu (Interim 0.1.5)
Subject: Re: "386BSD" trademark (fwd)
From: David Greenman <davidg@implode.rain.com>
Date: Sat, 19 Jun 93 17:26:02 -0700

> Okay folks.. taking new name suggestions.. we have:
>
> BSDFree86      - Rod, who is going with Jordans improved NON BSDI name..
> Free86BSD      - Jordan, Rod likes this one two...
>               - (F86BSD for short)
>
> vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv
>       v                                       v
>       v   This is the hat to drop yours in!   v
>       v                                       v
>       vvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv


*    How about just simply "FreeBSD"? No confusion, no fuss, seems like a good
* compromise to me. :-)

 ---

 -DG
```

http://www.freebsd.org/news/1993/freebsd-coined.html

---
# FreeBSD

* FreeBSD is an advanced operating system derived from BSD, the version of UNIX® developed at the University of California, Berkeley.
  * http://www.freebsd.org/about.html

.right[![Beastie](beastie.png)]

* BSD Family Tree
  * https://svnweb.freebsd.org/base/head/share/misc/bsd-family-tree?view=markup


---
# Who is using FreeBSD

FreeBSD is used in the devices from the world’s big companies:
* Apple
* Blue Coat
* Cisco
* F5 Networks
* Juniper
* NetApp
* Panasas
* Sony's PlayStation Family

---
# Who’s also using FreeBSD?

FreeBSD is also used to power some of the busiest sites on Internet:

* Apache
* ISC
* Netflix
  * Content delivery, approx 33% of US Internet traffic at night
* Pixnet
* WhatsApp
* Yahoo!
* Yandex

Facebook:  
"Our goal over the next few years is for the Linux kernel network stack to rival or exceed that of FreeBSD."  

---
# The projects based on / use parts of FreeBSD

* Based on
  * PC-BSD
  * m0n0wall
  * pfSense
  * FreeNAS
  * Debian GNU/kFreeBSD
  * Gentoo/FreeBSD
  * ArchBSD

* Using components
  * Chrome
  * OSv

---
# FreeBSD: The Good Parts

* BSD License
  * Designed to maximize commercial reuse
  * No requirement that derived works be open Source
  * Extensive use in commercial, research systems
* GEOM
* Netgraph
* Jail
* ZFS
* Dtrace
* MAC Framework
* Audit Framework
* Capiscum
* LLVM & Clang
* Ports/Pkg system
  * 20th birthday on 2014-08-21
And more..

---
# What's new for FreeBSD 11

https://wiki.freebsd.org/WhatsNew/FreeBSD11

* Some of these features will be merged to FreeBSD 10, even 9

---
# The FreeBSD Project is more than software

Global community of developers and users

.left-column[
* Developer community

  * Core team
  * Committers
  * Ports maintainers
  * Contributors

* FreeBSD Foundation
]

.right-column[
* User community

  * User groups
  * Vendors
  * Advocacy
  * Training
  * Certification
]

---
# Organization

svn://svn.freebsd.org/base/head/share/misc/organization.dot

```sh
$ dot -T png -o organization.png organization.dot
```

[organization.png](organization.png)

---
# FreeBSD Foundation

https://www.freebsdfoundation.org/

* Non-profit organization based in Boulder, CO
* Keep FreeBSD developers' heads warm
* Sponsored development
* Intellectual property, contracts, licensing, legal
* Developer travel grants
* Event sponsorship
* Hardware purchase
* Collaborative R&D agreements

* Blog
  * http://freebsdfoundation.blogspot.com/
* FreeBSD Journal
  * https://www.freebsdfoundation.org/journal

---

# What the Prject Produces

* FreeBSD kernel, user space
* Release engineering
* Security Advisories
* Errata Notices
* Ports collection, binary packages
* Manuals, handbook
* Web sites
* Community events
* Technical support, debugging, etc.

---

# Things We Consume
* Beer, soda, pizza, chocolate, and other vices
* Donated and sponsored Hardware
* Bandwidth
* Travel grants, salaries, contracts, grants
* Thanks, user testimonials, good press

---
# What does a committer do

* Shut up and code.
  * /etc/motd of freefall.FreeBSD.org

* Dogs and cats
  * https://wiki.freebsd.org/DogsOfFreeBSD
  * https://wiki.freebsd.org/CatsOfFreeBSD

---

# Who are the Committers

* http://svnweb.freebsd.org/base/head/usr.bin/calendar/calendars/calendar.freebsd?view=markup
* http://svnweb.freebsd.org/ports/head/astro/xearth/files/freebsd.committers.markers?view=markup

---
# FreeBSD Committers

* Committer is someone with right to commit to version control systems
* Selected based on key characteristics
  * Technical expertise
  * History of contribution to the FreeBSD Project
  * Ability to work well in the community
  * Having made these properties obvious!
* Key concept: mentor
  * Mentor proposes to core@ (portmgr@, doceng@)
  * Guide through first few months of committing

---
# FreeBSD Core Team

* Nine-member elected management body
  * Votes and candidates from the full set of active FreeBSD Committers
    * 2-year service
  * Core secretary
* Responsibilities
  * Administrative (commit bits, hats, team charters)
  * Strategic (project direction, coordination, cajoling)
  * Rules, conflict resolution, enforcement

---
# Groups and Projects

.left-column[
* Developers
  * Source Developers
  * Core Team
  * Core Team Secretary
  * Release Engineering Team
  * Release Engineering Build Teams
  * Security Officer
  * Security Team
  * Ports Team
  * Port Managers
  * Doceng Team
  * Documentation Team
  * Bugmaster
  * Vendor Relations Team
]

.right-column[
* Administrative
  * Foundation Board of Directors
  * Foundation Operations Manager
  * FreeBSD.org cluster admins
  * Mirrors Team
  * Donations Team
  * Marketing Team
  * VCS Admins
  * Postmaster
* Special Projects
  * Monthly Status Reports
  * SoC Mentors
  * Coverity Teams
  * FreeBSD CI Team
]

  http://www.freebsd.org/administration.html

---
# The FreeBSD Project Cluster

* Version Control
  * http://svn.freebsd.org
* Code Review
  * https://reviews.freebsd.org
* Continuous Integration
  * http://jenkins.freebsd.org
* World Wide Web
  * http://www.freebsd.org
* Mailing List
  * http://lists.freebsd.org
* Forum
  * http://forums.freebsd.org
* Wiki
  * http://wiki.freebsd.org
* Netperf Cluster
  * http://www.freebsd.org/projects/netperf/cluster.html

---
Mailing Lists

* Mostly public
  * Some expections (core, re, so, portgmr, course, ...)
* Organized loosely by topic
* Place where vast majority of FreeBSD discussion and planning takes Place
  * Both developer and user

http://lists.freebsd.org

---
# Lists you may want to know

.left-column[
* freebsd-announce
* freebsd-arch
* freebsd-arm
* freebsd-current
* freebsd-doc
* freebsd-drivers
* freebsd-dtrace
* freebsd-embedded
* freebsd-emulation
* freebsd-fs
* freebsd-geom
* freebsd-hackers
* freebsd-jail
* freebsd-jobs
* freebsd-multimedia
]
.right-column[
* freebsd-net
* freebsd-ports-announce
* freebsd-questions
* freebsd-security
* freebsd-stable
* freebsd-testing
* freebsd-toolchain
* freebsd-virtualization
* freebsd-xen
* svn-{src,ports,doc}-*
  * svn-{src,ports,doc}-head
  * svn-src-projects
* svn-doc-all
* soc-status
* https://mail.kde.org/mailman/listinfo/kde-freebsd
]

---
# Events

* AsiaBSDCon + DevSummit
* BSDCan + DevSummit
* DevSummit in Cambridge
* EuroBSDCon + DevSummit
* NYCBSDCon
* MeetBSD
* more...

---

# How We Got Here

https://wiki.freebsd.org/HowWeGotHere

When in doubt, just ask

---

# Ports collection

julian@: "src people make FreeBSD, and ports people make FreeBSD useful"

* Subbmitter
* Maintainer
* Committer
* Ports Teams
  * https://wiki.freebsd.org/PortsTeams

* Pkg(ng)

https://www.freebsd.org/ports/

---
# Ports jobs

* Daily works
  * Update ports
  * New ports
  * Issue reporting

* Not-so-daily works
  * Sweep commit

---

# The Document Project

* Handbook
* Web sites
* Articles
* Translation

https://www.freebsd.org/docs.html
---
# FreeBSD Developers in Taiwan

```sh
> grep Taiwan /usr/share/calendar/calendar.freebsd
```
```
01/12   Yen-Ming Lee <leeym@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1977
01/12   Ying-Chieh Liao <ijliao@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1979
01/14   Yi-Jheng Lin <yzlin@FreeBSD.org> born in Taichung, Taiwan, Republic of China, 1985
01/16   Vanilla I. Shu <vanilla@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1978
03/30   Po-Chuan Hsieh <sunpoet@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1978
05/22   Clive Tong-I Lin <clive@FreeBSD.org> born in Changhua, Taiwan, Republic of China, 1978
06/18   Li-Wen Hsu <lwhsu@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1984
07/17   Michael Chin-Yuan Wu <keichii@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1980
08/19   Chin-San Huang <chinsan@FreeBSD.org> born in Yi-Lan, Taiwan, Republic of China, 1979
09/03   Cheng-Lung Sung <clsung@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1977
09/20   Kevin Lo <kevlo@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1972
12/21   Rong-En Fan <rafan@FreeBSD.org> born in Taipei, Taiwan, Republic of China, 1982
```
also
```
Tai-hwa Liang <avatar@FreeBSD.org>
```


---

# Keeping Touch

* http://lists.freebsd.org/
* https://wiki.freebsd.org/RecentChanges

* Status Reports http://www.freebsd.org/news/status/status.html

* http://forums.freebsd.org/

* https://twitter.com/freebsdhelp

* http://bsdnow.tv/

---

# Call for Help

* IRC
  * https://wiki.freebsd.org/IrcChannels
  * https://wiki.freebsd.org/IrcNicks
* Mailing Lists
* Grab a committer :-)

---

# Contribute

* Send PR!
  * https://bugs.freebsd.org/bugzilla/
* Mailing Lists
* GSoC
* Translation

* Donation

---
# Ideas

https://wiki.freebsd.org/IdeasPage

---

# The FreeBSD Projects in Taiwan

* Traditional Chinese document translations

---

# Current Projects

* ARM
  * https://wiki.freebsd.org/FreeBSD/arm
  * https://wiki.freebsd.org/ARMTier1
  * https://wiki.freebsd.org/201407DevSummit/ARMv8
  * https://wiki.freebsd.org/arm64

* https://speakerdeck.com/kazuyoshi/porting-docker-to-freebsd

---

# Research

* Robert Watson
  * http://www.cl.cam.ac.uk/~rnw24/
  * http://www.cl.cam.ac.uk/research/security/ctsrd/
* Luigi Rizzo
  * http://info.iet.unipi.it/~luigi/

---

# Resources

* https://github.com/freebsd
* https://www.youtube.com/channel/UCntL6bw6PoFR0r67cMYXLkg

---

# Conclusion

* FreeBSD project one of thelargest, oldest, and most successful open source projects
  * Hundreds of committers, thousands of Contributors
  * Millions of lines of code
  * Tens of millions of deployed systems
* Highly successful community model makes it happen
  * Join this community!
  * -Ofun

---

# References

* How the FreeBSD Project Works
  * https://www.youtube.com/watch?v=Y0av1OOMKOA
* A Narrative History of BSD, Dr. Kirk McKusick
  * https://www.youtube.com/watch?v=ds77e3aO9nA
* Building and Running An Open-Source Community: The FreeBSD Project
  * https://www.youtube.com/watch?v=4xJFwkViJbc

* Twenty Years of Berkeley Unix 0 From AT&T-Owned to Freely Redistributable - Open Sources: Voices from the Open Source Revolution
  * http://oreilly.com/catalog/opensources/book/kirkmck.html

* BSD is Dying, Jason Dixon, NYCBSDCon 2007 https://www.youtube.com/watch?v=g7tvI6JCXD0
