---
title: Captive Portal API for Small Hotspot
abbrev: captivehs
docname: draft-thakore-hotspot-use-cases-latest
date: 2018-02-23
category: info

ipr: trust200902
area: Applications and Real-Time
workgroup: capport
keyword: hotspot

stand_alone: yes
pi: [toc, sortrefs]

author:
 -
    ins: D. Thakore
    name: Darshak Thakore
    organization: CableLabs
    email: d.thakore@cablelabs.com
    street: Postfach 330440
    city: Bremen
    code: D-28359
    country: Germany
    phone: +49-421-218-63921
    facsimile: +49-421-218-7000
 -
    ins: T. Derham
    name: Thomas Derham
    org: Broadcom
    email: thomas.derham@broadcom.com

normative:
  RFC2119:

informative:
  HOTSPOT20:
    target: https://www.wi-fi.org/file/hotspot-20-release-2-technical-specification-package-v110-0
    title: Hotspot 2.0 (Release 2) Technical Specification package

--- abstract

Put an abstract of the use case here.

--- middle

Introduction        {#problems}
============

Provide an introduction to hotspot and explain the infra needed
to deploy a hs system.


The Need for simpler mechanism   {#need}
------------------------------

Why and where will this use case help (mom and pop shops). What's better
with this compared to status quo


Basic Protocol Operation   {#ops}
========================

What's the initial architecture proposal if any.
Start with reference to captive portal api and how
we can leverage it for small hs use case

~~~~~~~~~~

   _________________________
   |  Put any figures /    |
   |      ascii art if     |
   |       required        |
   |                       |
   |_______________________|

~~~~~~~~~~
{: #figops title="Figure Arch"}

Security Considerations
=======================

Talk about issues with using self signed or bootstrap cert for captive
portal server https request.


--- back

Privacy Considerations
======================

Any privacy considerations we want to capture?
