---
title: Peering
sections:
  - type: FeatureHighlightSection
    colors: colors-f
    backgroundSize: inset
    title: Where did everyone go?
    text: >-
      Learn how top tech companies have learned working remote using our
      product.
    badge:
      type: Badge
      label: Case study
      styles:
        self:
          textAlign: left
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
      - type: Link
        label: Watch Video
        url: /
        style: link
        showIcon: true
        icon: playCircle
        iconPosition: left
    media:
      type: ImageBlock
      url: /images/network.svg
      altText: Team meeting
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-20
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-16
          - pl-16
          - pr-16
        justifyContent: center
        flexDirection: row
        alignItems: center
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: MediaGallerySection
    colors: colors-h
    title: ''
    subtitle: Trusted by
    images:
      - type: ImageBlock
        url: /images/apple.svg
        caption: Apple
        altText: Apple
      - type: ImageBlock
        url: /images/google-play.svg
        caption: Google Play
        altText: Google Play
      - type: ImageBlock
        url: /images/playstation.svg
        caption: PlayStation
        altText: PlayStation
      - type: ImageBlock
        url: /images/gatsby.svg
        caption: Gatsby
        altText: Gatsby
      - type: ImageBlock
        url: /images/xbox.svg
        caption: Xbox
        altText: Xbox
      - type: ImageBlock
        url: /images/skype.svg
        caption: Apple
        altText: Apple
      - type: ImageBlock
        url: /images/zcool.svg
        caption: ZCOOL
        altText: ZCOOL
    columns: 7
    spacing: 3
    imageSizePx: 240
    aspectRatio: auto
    showCaption: false
    enableHover: false
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
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - elementId: ''
    colors: colors-a
    title: The Section Title
    subtitle: ''
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
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
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - elementId: ''
    colors: colors-e
    title: The Section Title
    subtitle: The section subtitle
    text: >
      Toronto\<!---->\<!---->\<!---->\<!---->




      *   andrewnet has a very open peering policy for his Toronto pop and is
      willing to peer through a mutual exchange or through a tunnel (vxlan
      preferred).


      <!---->


      *   andrewnet's Toronto peering router is located with the upstream,
      [GoCodeIt](https://bgp.he.net/AS62513). This box is hosted on the cloud
      provider, [Xenyth](https://xenyth.net/?affid=29) at Equinix TR2.


      <!---->


      *   the range broadcasted from this pop is
      [2602:fc26:6::/48](https://bgp.he.net/net/2602:fc26:6::/48).


      ## New Jersey


      *   andrewnet does have a selective policy for who is able to peer with
      his New Jersey/New York pop due to the fact that he runs a production
      connection off of this.


      *   andrewnet's New Jersey pop obtains transit over a GRE tunnel to
      upstream [Global Secure Layer](https://bgp.he.net/AS137409).


      *   the range broadcasted from this pop are
      [2605:f440:6969::/48](https://bgp.he.net/net/2605:f440:6969::/48),[
      2602:fc26::/48](https://bgp.he.net/net/2602:fc26::/48), and
      [45.41.37.0/24](https://bgp.he.net/net/45.41.37.0/24).


      ## Netherlands


      *   andrewnet has a very open peering policy for his Netherlands pop and
      is willing to peer through a tunnel (vxlan preferred).


      <!---->


      *   andrewnet's Netherlands peering router is located with the upstream,
      [Bakker IT](https://bgp.he.net/AS44103).


      <!---->


      *   the range broadcasted from this pop is
      [2a0e:fd45:2b00::/44](https://bgp.he.net/net/2a0e:fd45:2b00::/44).


      # Fremont


      *   andrewnet has a very open peering policy for his Fremont pop and is
      willing to peer through a tunnel (vxlan preferred).


      *   andrewnet's Fremont peering router is located with the upstream, [Eric
      ](https://ericz.me/)at Hurricane Electric's FMT2 Data Center.


      *   the range broadcasted from this pop is
      [2602:fc26:2::/48](https://bgp.he.net/net/2602:fc26:2::/48).


      # Kansas City


      *   andrewnet has a very open peering policy for his Kansas City pop and
      is willing to peer through a tunnel (vxlan preferred).


      *   andrewnet's MCI peering router is located with the upstream,
      [Fosshost](https://fosshost.org/).


      *   the range broadcasted from this pop is
      [2602:fc26:8::/48](https://bgp.he.net/net/2602:fc26:8::/48).Network Map
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
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - type: FeaturedItemsSection
    colors: colors-a
    title: Remote doesn’t mean alone. Here are so great features
    subtitle: >-
      These are all excellent features that will provide exactly the things
      you’re looking for.
    items:
      - type: FeaturedItem
        title: Faster
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/faster.svg
          altText: Item image
        styles:
          self:
            textAlign: left
            padding:
              - pt-4
              - pb-6
              - pl-4
              - pr-4
            borderColor: border-dark
            borderStyle: solid
            borderWidth: 1
      - type: FeaturedItem
        title: Smarter
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/smarter.svg
          altText: Item image
        styles:
          self:
            textAlign: left
            padding:
              - pt-4
              - pb-6
              - pl-4
              - pr-4
            borderColor: border-dark
            borderStyle: solid
            borderWidth: 1
      - type: FeaturedItem
        title: Focused
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          type: ImageBlock
          url: /images/focused.svg
          altText: Item image
        styles:
          self:
            textAlign: left
            padding:
              - pt-4
              - pb-6
              - pl-4
              - pr-4
            borderColor: border-dark
            borderStyle: solid
            borderWidth: 1
    columns: 3
    enableHover: false
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: FeatureHighlightSection
    colors: colors-a
    title: 'A great feature, we’re proud of'
    text: >-
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
      - type: Link
        label: Learn More
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero section image
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
          - pt-36
          - pb-6
          - pl-4
          - pr-4
        justifyContent: center
        flexDirection: row
        alignItems: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeatureHighlightSection
    colors: colors-a
    title: And a strong value proposition
    text: >-
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
      - type: Link
        label: Learn More
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/hero-2.png
      altText: Hero section image
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
          - pt-6
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        flexDirection: row-reverse
        alignItems: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    colors: colors-a
    variant: variant-b
    title: >-
      We sometimes write things. You should read it, it might shed some  light
      on why we’re doing what we’re doing
    actions:
      - type: Link
        label: See all posts
        url: /blog
        showIcon: true
        icon: arrowRight
        iconPosition: right
    showDate: true
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
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
          - pt-0
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FaqSection
    colors: colors-f
    title: Need Answers?
    subtitle: ''
    actions:
      - type: Link
        label: See all
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
    items:
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
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
          - pt-20
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: TestimonialsSection
    colors: colors-a
    variant: variant-a
    title: ''
    subtitle: ''
    testimonials:
      - quote: >-
          ## Such a great experience to be using this product. It really helped
          with what I needed help with.
        name: Carla Rogers
        title: Happy customer
        image:
          type: ImageBlock
          url: /images/carla.jpg
          altText: Photo of Carla Rogers
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
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Get early access
    text: >-
      Sign up your team today to be the first to try out our new product to
      increase your team's productivity.
    form:
      type: FormBlock
      elementId: sign-up-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: 'true'
          width: full
      submitLabel: Sign Up
      styles:
        submitLabel:
          textAlign: center
    media: null
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pl-12
          - pr-12
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
layout: PageLayout
---