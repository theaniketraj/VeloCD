---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Where Speed Powers CI/CD
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Experience the Future of Continuous Integration. VeloCD accelerates your
      Builds and Deployments with Real-Time Monitoring and Intelligent
      Automation.
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Explore DOCS
        altText: VeloCD DOCS
        url: 'https://velocd-docs.netlify.app'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Velocd
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
      subtitle:
        fontWeight: 400
  - type: FeaturedItemsSection
    title:
      text: Key Features
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: at a glance
    items:
      - type: FeaturedItem
        title: Real-Time CI/CD Pipeline Visualization
        subtitle: ''
        text: >+
          VeloCD offers an **interactive, real-time visualization** of your
          CI/CD pipelines. Track every build, test, and deployment in **live
          motion**, with dynamic status indicators that reflect changes
          instantly. See green dots for successful stages and red for failures,
          allowing you to **identify bottlenecks at a glance**.

        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Blockchain Powered Verification
        subtitle: ''
        text: >
          Ensure the **integrity and authenticity** of your deployment process
          with VeloCD’s **blockchain-based verification**. Each build and
          deployment is cryptographically recorded, making it **tamper-proof and
          auditable**. This ensures that your software’s integrity is preserved,
          providing **trust and security** in every release.
        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Kubernetes Orchestrated CI/CD
        subtitle: ''
        text: >
          VeloCD brings **Kubernetes powered orchestration** into your CI/CD
          pipeline, enabling **scalable and containerized** deployments.
          Automatically spin up and manage multiple environments in parallel,
          reducing deployment time and optimizing resource utilization.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: VeloCD
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Unleash the Velocity in your CI/CD.
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Overview
    text: >
      VeloCD centralizes and automates the management of software versions and
      deployment pipelines. Its design is grounded in a modular architecture
      that enables precise control over version incrementation, branching,
      tagging, and rollback mechanisms. The platform facilitates a seamless
      workflow from source code management to deployment, reducing manual
      intervention and mitigating risks associated with human error.
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: VeloCD
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
    type: GenericSection
  - type: GenericSection
    title:
      text: Automated Version Management
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: ''
    text: >
      Implements semantic versioning based on commit metadata, ensuring that
      major, minor, and patch updates are applied automatically. This module
      provides detailed audit trails and facilitates rollback operations with
      precision.
    actions: []
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Flexible Deployment Models
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Designed for diverse operational environments, VeloCD supports local
      execution as a native desktop application, cloud-based deployments,
      on-premises hosting, and containerized solutions through Docker and
      Kubernetes. This flexibility accommodates both small-scale and
      enterprise-level infrastructures.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Explore DOCS
        url: 'https://velocd-docs.netlify.app'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
        altText: VeloCD's DOCS
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Security & Compliance
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Enforces strict security protocols including role-based access control
      (RBAC), multi-factor authentication, and comprehensive audit logging.
      These measures ensure data integrity and compliance with industry
      standards.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Explore DOCS
        url: 'https://velocd-docs.netlify.app'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
        altText: VeloCD's DOCS
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title:
      text: VeloCD's Advanced Capabilities
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Explore Exhaustive features in our DOCS.
    items:
      - title: Intelligent Dependency Management
        tagline: ''
        subtitle: ''
        text: >
          VeloCD offers **Intelligent Dependency Management**, automatically
          resolving and managing project dependencies with **version
          compatibility checks** and real-time validation. It detects outdated
          or vulnerable dependencies and suggests secure, up-to-date
          alternatives.
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
      - title: Secure Role-Based Access Control (RBAC)
        tagline: ''
        subtitle: ''
        text: >
          VeloCD integrates **Secure RBAC**, allowing organizations to define
          and manage user permissions with precision. Assign granular access
          levels to developers, testers, and admins, ensuring **only authorized
          personnel** can modify or deploy code.
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
      - title: Automated Change Tracking & Audit Logs
        tagline: ''
        subtitle: ''
        text: >
          VeloCD provides **Automated Change Tracking & Audit Logs**, recording
          every modification, build, and deployment event with timestamps. This
          enables **detailed traceability** and makes it easy to review
          historical changes for debugging or compliance audits.
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
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
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
        label: Submit
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
  metaTitle: Home - VeloCD
  metaDescription: Unleash the velocity in your CI/CD.
  socialImage: /images/main-hero.jpg
  type: Seo
  addTitleSuffix: true
  metaTags:
    - type: MetaTag
      property: 'og:title'
      content: VeloCD
type: PageLayout
---
