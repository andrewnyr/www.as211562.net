---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-b
    text: |
      ## welcome to the homepage of my network, as211562.
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
          - pb-16
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: information
    text: >+
      we announce a few different ipv4 and ipv6 prefixes to the dfz. you can
      view some information about our network here.




      this mainly exists for educational purposes as i navigate the intricacies
      of advanced network topologies.

    actions:
      - type: Button
        label: Abuse
        url: /abuse
        style: secondary
      - label: PeeringDB
        altText: ''
        url: 'https://www.as211562.net/peeringdb'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: BGP Tools
        altText: ''
        url: 'https://www.as211562.net/tools'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: BGP.HE.NET
        altText: ''
        url: 'https://www.as211562.net/hurricane'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    backgroundImage: null
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
    backgroundSize: full
    title: supporters
    text: >
      *   <https://www.bakker-it.eu> -IPv6 Prefix(s) and Compute


      *   <https://kagl.me> -IPv6 Prefix(s)


      *   <https://globalsecurelayer.com> -BGP Tunnel


      *   [https://as206628.net](https://as206628.net/) -Compute


      *   <https://www.xenyth.net> -Waived BGP Fee


      andrewnet is a small network operated by a broke college student. if you
      would like to support me in my goals by hosting a node, providing a
      tunnel, or allocating a prefix, please [contact
      me](https://www.as211562.net/contact/).
    actions:
      - type: Button
        label: contact
        url: /
        style: primary
    backgroundImage: null
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
    title: our network
    subtitle: thanks to bgp.he.net
    badge:
      elementId: ''
      styles:
        self:
          textAlign: left
    actions: []
    media:
      type: ImageBlock
      url: 'https://bgp.he.net/graphs/as211562-ipv6.svg'
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
---
