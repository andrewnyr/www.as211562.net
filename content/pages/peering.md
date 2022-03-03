---
title: peering
sections:
  - colors: colors-e
    elementId: ''
    title: peering & network information
    subtitle: ''
    jobLists: []
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: JobsSection
  - colors: colors-a
    elementId: ''
    subtitle: ''
    jobLists:
      - type: JobList
        items:
          - type: JobListItem
            text: >+
              ### Toronto


              *   you can expect 2602:fc26:6::/48, 2602:fc26:7::/48, and
              2602:fc26:a::/48 to be announced to the dfz from toronto, with
              2602:fc26::/48 and 45.41.37.0/24 announced only to private or
              bilat peers.

              *   i have a very open peering policy for my toronto pop and i am
              willing to peer through a mutual exchange or through a tunnel
              (vxlan preferred).

              *   tor01 is located with the upstream, [GoCodeIt
              ](https://bgp.he.net/AS62513)hosted on the cloud provider,
              [Xenyth](https://xenyth.net/?affid=29) at equinix tr2. tor02 is an
              oracle cloud vm with sub-ms latency to tor01.


              ### New Jersey


              *   you can expect 45.41.37.0/24, 2602:fc26::/48,
              2602:fc26:1::/48, and 2602:fc26:a::/48 to be announced to the dfz
              from new jersey.

              *   i do have a selective policy for who is able to peer with my
              new jersey/new york pop due to the fact that i run a production
              connection off of this.

              *   my new jersey pop obtains transit over a gre tunnel to
              upstream [Global Secure Layer](https://globalsecurelayer.com/),
              also featuring a backup link through [GoCodeIt
              ](https://xenyth.net/?affid=29)and connections to my other pops.

              *   you can view a diagram of the network layout of this pop
              [here](https://cdn.andrewnet.net/ShareX/2022/02920f81cb-d3e7-4d2a-8747-6eeb2d9c148e/nyc01.drawio.html).


              ### London


              *   you can expect 2602:fc26:14::/48 to be announced to the dfz
              from london.

              *   i have a very open peering policy for my london pop and am
              willing to peer on [Rapid-IX ](https://rapidix.net/)or through a
              tunnel (vxlan preferred).

              *   my london peering router is located with the upstream,[
              Inferno Communications](https://infernocomms.com/), who [i love
              very much](https://www.as211562.net/inferno/).


              ### Netherlands


              *   you can expect 2602:fc26:4::/48 to be announced to the dfz
              from netherlands.


              *   i have a very open peering policy for my netherlands pop and
              am willing to peer through a tunnel (vxlan preferred).


              *   my netherlands peering router is located with the upstream,
              [Bakker IT](https://bgp.he.net/AS44103).


              ### Fremont


              *   you can expect 2602:fc26:2::/48 to be announced to the dfz
              from fremont. 


              *   i have a very open peering policy for my fremont pop and am
              willing to peer through a tunnel (vxlan preferred).


              *   my fremont peering router is located with the upstream, [Eric
              ](https://ericz.me/)at hurricane electric's fmt2 data center.


              ### Kansas City


              *   you can expect 2602:fc26:8::/48 to be announced to the dfz
              from mci01 with 2602:fc26:12::/48 from mci02. 


              *   i have a very open peering policy for my kansas city pop and
              am willing to peer through a tunnel (vxlan preferred).


              *   my mci01 peering router is located with the upstream,
              [Fosshost](https://fosshost.org/). my mci02 peering router is
              located with the upstream, [Misaka
              Network](https://www.misaka.io/).

            actions: []
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-0
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: JobsSection
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    actions: []
    backgroundImage:
      url: /images/andrewnet-mosaic.svg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
layout: PageLayout
metaDescription: peering is how the internet works! peer with me today!
---
