---
title: home
layout: PageLayout
sections:
  - type: CtaSection
    elementId: ''
    colors: colors-f
    title: welcome to the homepage of as1003
    actions: []
    backgroundImage:
      type: ImageBlock
      url: /images/grad.svg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
      styles:
        self:
          opacity: 100
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    backgroundSize: full
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: information
    text: >
      i announce a few different ipv4 and ipv6 prefixes to the dfz. you can view
      some information about my network here.


      this mainly exists for educational purposes as i navigate the intricacies
      of advanced network topologies.


      andrewnet production is based on as1003, while andrewnet experimental is
      centered around as211562.
    actions:
      - label: PeeringDB
        altText: ''
        url: 'https://www.peeringdb.com/asn/1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: BGP Tools
        altText: ''
        url: 'https://bgp.tools/as/1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: BGP.HE.NET
        altText: ''
        url: 'https://bgp.he.net/AS1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: QRATOR
        altText: ''
        url: 'https://radar.qrator.net/as1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: IRR Explorer
        altText: ''
        url: 'https://irrexplorer.nlnog.net/asn/AS1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: IPinfo
        altText: ''
        url: 'https://ipinfo.io/AS1003'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: ARIN Whois
        altText: ''
        url: 'https://search.arin.net/rdap/?query=AA-2909'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    backgroundImage: null
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        alignItems: flex-start
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
  - elementId: ''
    colors: colors-c
    title: supporters
    text: >
      *   <https://globalsecurelayer.com> -BGP & DDOS Protection


      *   [https://as206628.net](https://as206628.net/) -Compute


      *   <https://www.xenyth.net> -Waived BGP Fee


      *   [https://forksystems.net](http://forksystems.net/) -Compute


      *   <https://www.bakker-it.eu> -Compute


      *   [https://ioharbor.com](https://ioharbor.com/) -Compute


      andrewnet is a small network operated by a broke college student. if you
      would like to support me in my goals by hosting a node, providing a
      tunnel, or allocating a prefix, please [contact
      me](https://www.as1003.net/contact/).
    actions:
      - type: Button
        label: contact
        url: 'https://www.as1003.net/contact/'
        style: primary
    backgroundImage:
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
        width: wide
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
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: my network
    subtitle: illustrated by bgp.he.net
    badge:
      elementId: ''
      styles:
        self:
          textAlign: left
    actions: []
    media:
      type: ImageBlock
      url: 'https://bgp.he.net/graphs/as1003-ipv6.svg'
      altText: network map
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
          - pt-14
          - pb-14
          - pl-14
          - pr-14
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeatureHighlightSection
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
addTitleSuffix: true
metaDescription: the official network of andrewnet
---
