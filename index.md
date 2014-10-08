---
layout: top
title: Fiber
---

Fiber is a suite of miniapps that are maintained and developed at RIKEN Advanced Institute for Computational Science (RIKEN AICS).

### News

{% comment %}
See for template syntax and semmatics at https://github.com/Shopify/liquid/wiki/Liquid-for-Designers
{% endcomment %} 
<ul class="posts">
{% for post in site.posts limit:5 %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

See the [full archive of news](news).

### Miniapps

- **CCS QCD**: A QCD miniapp originally developed by Kenichi Ishikawa (Hiroshima University), et al.
<br /> [[Download source](https://github.com/fiber-miniapp/ccs-qcd/archive/1.1.1.zip)] [[View development repository](http://github.com/fiber-miniapp/ccs-qcd)]
- **FFVC-MINI**: A Navier-Stokes solver for 3D unsteady thermal flow of incompressible fluid. Derived from the FFVC simulation program developed by Kenji Ono (RIKEN AICS), et al. <br />
[[Download source](https://github.com/fiber-miniapp/ffvc-mini/archive/1.0.1.zip)] [[View development repository](http://github.com/fiber-miniapp/ffvc-mini)]
- **NICAM-DC-MINI**: A miniapp based on NICAM-DC that is derived from NICAM (Nonhydrostatic ICosahedral Atmospheric Model).  <br />
[[Download source](https://github.com/fiber-miniapp/nicam-dc-mini/archive/1.0.tar.gz)]
[[View development repository]( https://github.com/fiber-miniapp/nicam-dc-mini)]
- **mVMC-MINI**: A suite of mVMC program and test data.  mVMC analyzes the physical characteristics of the strongly correlated electron systems.
<br />
[[Download source](https://github.com/fiber-miniapp/mVMC-mini/archive/1.0.tar.gz)]
[[View development repository]( https://github.com/fiber-miniapp/mVMC-mini)]
- **NGS Analyzer-MINI**: A miniapp for genome analysis.  NGS Analyzer performs human genome analysis to identify genetic differences among persons or cancer cell's mutations.
<br />
[[Download source](https://github.com/fiber-miniapp/ngsa-mini/archive/1.0.tar.gz)]
[[View development repository]( https://github.com/fiber-miniapp/ngsa-mini)]
- **MODYLAS-MINI**: A miniapp based on a general-purpose molecular dynamics simulation program MODYLAS. <br />
[[Go to download site](http://hpci-aplfs.aics.riken.jp/fiber/modylas-mini.html)]


### Documentation

Information on each miniapp, such as build instructions and exeuction configurations, can be found in its own source package. Here's a list of some of the recent slides and papers on the overall Fiber miniapps:

- (*Japanese*) *Fiber Miniapp Overview*, SWoPP 2014 workshop, July 2014. [[slides](https://github.com/fiber-miniapp/fiber/raw/master/fiber-swopp2014-slides.pdf)]
- *Miniapps for Enabling Architecture-Application Co-design for Exascale Supercomputing*, 19th Workshop on Sustained Simulation Performance, March 2014. [[slides](https://github.com/fiber-miniapp/fiber/raw/master/fiber-wssp2014-slides.pdf)]
- *Mini-App Effort in Japan*, SC13 BoF: Library of Mini-Applications for Exascale Component-Based Performance Modeling, November 2013. [[slides](https://github.com/fiber-miniapp/fiber/raw/master/fiber-sc13bof-slides.pdf)]

### Mailing List

New miniapps and version upgrades will be announced at the [Users Group mailing list](https://groups.google.com/d/forum/fiber-miniapp-users). Subscribe the list by sending an empty email to <fiber-miniapp-users+subscribe@googlegroups.com> or get [RSS updates](https://groups.google.com/forum/feed/fiber-miniapp-users/msgs/rss.xml?num=15).

### Fiber Developers

- Naoya Maruyama ([RIKEN AICS](http://www.aics.riken.jp))
- Soichiro Suzuki ([RIKEN AICS](http://www.aics.riken.jp))
- Kazunori Mikami ([RIKEN AICS](http://www.aics.riken.jp))
- Yukihiro Komura ([RIKEN AICS](http://www.aics.riken.jp))
- Shinichiro Takizawa ([RIKEN AICS](http://www.aics.riken.jp))
- Motohiko Matsuda ([RIKEN AICS](http://www.aics.riken.jp))

### Collaborators

- Satoshi Matsuoka, Akihiro Nomura (Tokyo Tech)
- Takahiro Katagiri (University of Tokyo)

### Acknowledgments

The initial development of Fiber was part of an HPCI Feasibility Study project (FY2012-FY2013) led by RIKEN AICS and Tokyo Institute of Technology, which was funded by Ministry of Education, Culture, Sports, Science and Technology, Japan.

