---
title: Home
sections:
  - type: hero_section
    title: ¡El mejor lugar para trabajar!
    subtitle: >-
      Trabajar en nuestras oficinas es sinónimo de pasarla bien, trabajas a tu
      manera, aprendes continuamente, desarrollas tu carrera, creas lazos
      sólidos con compañeros que se convierten en familia, busques lo que
      busques con nosotros puedes impulsar tu camino.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
        has_icon: false
    image: images/hero.png
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: none
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    background_image: /images/watercolor.png
  - type: features_section
    title: QUIENES SOMOS
    subtitle: What I do
    features:
      - title: Content Creation
        subtitle: 'Website, blog, social media and more.'
        content: >+
          En Micall Group, creemos que un trabajo es más que un lugar, es un
          compañero de camino, por eso, creamos oportunidades basadas en las
          personas, para empoderarlas y guiarlas al éxito profesional.

        actions:
          - label: See Writing Samples
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/confident-call-center-operator-talking-with-client.jpg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Online Store Management
        subtitle: 'Product updates, inventory and pricing.'
        content: >-
          Managing an online business is a full-time job. I will make sure your
          products look great, sound great, and sell more on your choice of
          ecommerce platform.
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-2.svg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: Technical Content
        subtitle: 'Your products and services, at scale.'
        content: >-
          I will dive into the ins and outs of your product or service and make
          sure the right information is communicated throughout your
          documentation, pamphlets, manuals and technical documents.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: secondary
  - section_id: lorem-ipsum
    title: lorem-ipsum
    subtitle: lorem-ipsum
    content: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    actions: []
    image_alt: lorem-ipsum
    video_embed_html: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua.
    media_position: top
    media_width: fifty
    align: left
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: hero_section
  - type: grid_section
    title: NUESTROS CLIENTES
    subtitle: Con la confianza de empresas grandes y pequeñas
    align: center
    grid_items:
      - image: /images/2.jpg
        image_alt: Logo 1
        image_align: center
      - image: /images/BBG3znOy_400x400.jpg
        image_alt: Logo 2
        image_align: center
      - image: /images/711px-Orange_logo.svg.png
        image_alt: Logo 3
        image_align: center
      - image: /images/gwimeOoz_400x400.jpg
        image_alt: Logo 4
        image_align: center
      - image_alt: Logo 5
        image_align: center
      - image_alt: Logo 6
        image_align: center
      - image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    background_image_size: auto
    actions: []
    background_color: none
  - type: grid_section
    title: Testimonials
    subtitle: What My Clients Say
    grid_items:
      - content: >-
          Alyvia is an amazing content writer. She helped us produce microcopy
          for our apps in all levels of user touchpoints.


          **Hanson Deck,** *App Developer, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Alyvia really understands who our customers are and what tone of voice
          to use when communicating with them.


          **Miles Tone,** *CEO, Studio*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Working with Alyvia was great because she was well versed in all of
          our tools and applications, and was able to manage our store and
          campaigns without any technical glitches.


          **Eleanor Carr,** *CTO, eCommerce Business*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >-
          I love it when a content writer can really wordsmith and create copy
          that suits the design intention and style!


          **Gordon Norman,** *Web Designer, Local Business*
        image: images/gordon-norman.png
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nombres y apellidos
        label: Name
        default_value: Nombre y apellido
        is_required: true
      - input_type: number
        name: Móvil de contacto
        label: Móvil de contacto
        default_value: Número celular
        options: []
        is_required: false
      - input_type: email
        name: email
        label: Email
        default_value: Tu correo electrónico
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactados.
        is_required: true
    submit_label: Postular
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
