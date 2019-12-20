---
title: "Testing stuff"

views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
---
<DIV class="test">
Test sida
=========================
</DIV>

Testar olika designprinciper.

Hierarchy, framing, scale and direction
------------
[FIGURE src="image/B-cat.jpg?w=100&crop-to-fit&area=12,30,53,25" class="center" alt="Cats"]
<p></p>

[FIGURE src="image/B-cat.jpg?w=200&crop-to-fit&area=12,30,53,25" class="center" alt="Cats"]
<p></p>

[FIGURE src="image/B-cat.jpg?w=300&crop-to-fit&area=12,30,53,25" class="center megaborder" alt="Cats"]

Where were your eyes pulled and in what direction did you continue to look?

Balance
--------
[FIGURE src="image/B-bridge.jpg?w=200&f=negate" class="left" alt="Bridge"]
[FIGURE src="image/B-bridge.jpg?w=100&area=30,15,10,70" class="left" alt="Bridge"]
[FIGURE src="image/B-bridge.jpg?w=200&f=negate" class="left" alt="Bridge"]

<div class="clearboth"></div>

[FIGURE src="image/B-bridge.jpg?w=543&r=180&area=30,0,30,15" class="left" alt="Bridge" caption="Do you see the face?"]

Unbalanced
----------
[FIGURE src="image/B-bridge.jpg?w=100&area=30,15,10,70" class="center" alt="Bridge"]
[FIGURE src="image/B-bridge.jpg?w=200&f=negate" class="left" alt="Bridge"]
[FIGURE src="image/B-bridge.jpg?w=543&area=30,0,30,0" class="left" alt="Bridge"]
[FIGURE src="image/B-bridge.jpg?w=200&f=negate" class="right" alt="Bridge"]

<div class="clearboth"></div>

Messy?
