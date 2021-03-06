---
title: Home
layout: PageLayout
colors: colors-a
backgroundImage:
  url: /images/background-240d3ac2.gif
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: repeat-y
  opacity: 30
sections:
  - elementId: title
    colors: colors-f
    backgroundSize: full
    title: In Memory of Ellie Guner
    subtitle: 1997-2022
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: memorys
    actions:
      - label: See All
        altText: view memories
        url: /memories
        showIcon: true
        icon: playCircle
        iconPosition: left
        style: secondary
        elementId: see all
        type: Button
    showDate: true
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-a
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 3
        borderStyle: double
        borderColor: border-dark
        borderRadius: medium
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    title: Memories
  - colors: colors-f
    elementId: ''
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/friends-ae75ad82.jpg
        altText: Image one
        caption: Image one caption
      - type: ImageBlock
        url: /images/20160524_204158.jpg
        altText: Image two
        caption: Image two caption
      - type: ImageBlock
        url: /images/7F250CA8-6B34-4317-9AA7-0B5337BEB2F4.jpg
        altText: Image three
        caption: Image three caption
      - type: ImageBlock
        url: /images/20140721_192235-MIX.jpg
        altText: Image four
        caption: Image four caption
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
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
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - colors: colors-f
    elementId: ''
    title: Gallery
    images:
      - type: ImageBlock
        url: /images/20161123_195736.jpg
        altText: Image one
        caption: Image one caption
      - type: ImageBlock
        url: /images/20160730_174636.jpg
        altText: Image two
        caption: Image two caption
      - type: ImageBlock
        url: /images/IMG_9510.jpg
        altText: Image three
        caption: Image three caption
      - type: ImageBlock
        url: /images/942235_414007195372886_786325893_n.jpg
        altText: Image four
        caption: Image four caption
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
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
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - colors: colors-f
    elementId: ''
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/106600482_3634004779946974_251702395566757051_n.jpg
        altText: Image one
        caption: Image one caption
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: /images/61871_333202573453349_1705792927_n.jpg
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        type: ImageBlock
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
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
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
  - title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-36
          - pb-36
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
    type: DividerSection
  - type: FeaturedPostsSection
    elementId: eulogy
    colors: colors-f
    variant: variant-d
    showFeaturedImage: true
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-seven.md
      - content/pages/blog/post-six.md
      - content/pages/blog/post-one.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    showAuthor: true
    title: Eulogy(s)
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Wanna Share A Story About Ellie??
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
      submitLabel: "Submit\U0001F415"
      styles:
        submitLabel:
          textAlign: center
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
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
addTitleSuffix: true
metaDescription: Ellie Guner
metaTitle: memory
socialImage: /images/66881054_3094379133907374_8699886776979816448_n-a3ad8b1e.jpg
---
