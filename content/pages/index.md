---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Empower your team with Agile BA
      color: text-dark
      type: TitleBlock
    subtitle: Collaborate & deliver value faster
    text: >
      From user story mapping to backlog prioritization, business analysts
      ensure the team stay aligned, delivers value iteratively, and adapts to
      change effortlessly.
    actions:
      - label: Learn more..
        altText: ''
        url: 'https://hoangsol.com/category/agile-business-analysis/'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/45. startup-3.png
      altText: Seamlessly integrate business analysis into Agile workflows
      elementId: ''
      type: ImageBlock
    badge:
      label: Agile business analysis
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - posts: []
    showThumbnail: false
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Workshops and Training Programs
      color: text-dark
      type: TitleBlock
    subtitle: >-
      Join our regular workshops and training sessions designed to enhance your
      skills.
    text: >+
      Whether you are a beginner or an experienced professional, our program are
      tailored to meet your needs.


      *   **Interactive Workshops.** Hands-on sessions to practice real-world
      techniques.


      *   **Expert-Led Training.** Learn from industry professionals with years
      of experience.


      *   **Flexible Options.** Online and in-person sessions available for your
      convenience.

    actions:
      - label: Schedule a call
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/BA-Day-logo.jpg
      altText: ''
      type: ImageBlock
    badge:
      label: Accelerate your career in business analysis
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Market Research Reports
      color: text-dark
      type: TitleBlock
    subtitle: Gain actionable insights
    text: >+
      Whether you're exploring new opportunities or refining your strategies,
      our reports provide the data and analysis you need to make informed
      decisions.


      *   **Tailored for your business.** Insights customized to your industry
      and goals.


      *   **Data-driven decisions.** Leverage reliable data to identify
      opportunities and mitigate risks.


      *   **Stay ahead of trends.** Keep up with emerging trends and market
      shifts.

    actions:
      - label: Our MPR Library
        url: 'https://www.baocao.site/'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/Screenshot 2024-11-24 at 16.04.18.png
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: Drive business forward
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Featured Projects
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Featured items section subtitle
    items:
      - title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify Create site.
        image:
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: >
          Learn from the tutorial and build your first awesome Netlify Create
          site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title:
      text: Looking for business analysis professionals?
      color: text-dark
      type: TitleBlock
    subtitle: We are here to assist
    text: |
      Fill out the form below, and our team will get back to you shortly.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: 'Submit, and let''s start building solutions together!'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Hoang Sol
  metaDescription: Business Analysis as a Service
  socialImage: /images/Hoang.jpeg
  type: Seo
type: PageLayout
---
