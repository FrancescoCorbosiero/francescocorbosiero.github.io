---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Alimenta il tuo cane con passione e conoscenza per una vita sana e vigorosa.
      text: Come esperto di nutrizione canina, mi impegno a fornire piani alimentari personalizzati per soddisfare le esigenze specifiche del tuo cane. La mia esperienza e conoscenza garantiscono una salute ottimale, prevenendo malattie e migliorando il benessere generale del tuo compagno a quattro zampe.
      primary_action:
        text: Prenota una consulenza gratuita!
        url: https://wa.me/393476780938
        icon: rocket-launch
      #secondary_action:
      #  text: Contatti
      #  url: https://wa.me/393476780938
      announcement:
        text: "Consulenze personalizzate e consigli nutrizionali per il benessere del tuo amico a quattro zampe."
        link:
          text: "Leggi il mio blog"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: hero.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "10+"
          description: |
            Anni di esperienza  
            nel settore
        - statistic: "100+"
          description: |
            Clienti 
            soddisfattti
        - statistic: "1k+"
          description: |
            Più di mille consulenze 
            annuali
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: Features
  #     text: Build your site with blocks 🧱
  #     items:
  #       - name: Optimized SEO
  #         icon: magnifying-glass
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #       - name: Fast
  #         icon: bolt
  #         description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #       - name: Easy
  #         icon: sparkles
  #         description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: Swappable Blocks
  #         icon: rectangle-group
  #         description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: features
    content:
      items:
        - title: Andrea Bellettati
          text: Esperto in nutrizione per cani
          feature_icon: check
          features: 
          - "Mi chiamo Andrea Bellettati, Educatore Cinofilo. Ho abbandonato gli approcci stereotipati per dare ai cani la libertà di esprimersi.
        Organizzo giornate che hanno come obiettivo rendere il cane libero di potersi esprimere in contesti naturali in compagnia dei propri umani di riferimento.
        Grazie alla mia bassotta Athena, inappetente sin dalla nascita, mi sono appassionato di alimentazione e integrazione.
        Nella mia vita lavorativa ho potuto osservare come una sana e corretta alimentazione e una vita che rispetti le esigenze etologiche dell'animale siano strettamente legate e imprescindibili l'una dall'altra affinchè si possa raggiungere uno stato di benessere.
        Clicca qui sotto per metterti in contatto con me!"
          # Upload image to `assets/media/` and reference the filename here
          image: features-1.png
          button:
            text: Prenota una consulenza gratuita!
            url: https://wa.me/393476780938
        - title: "La mia Community: Team Branco"
          text: Se il tuo animale...
          feature_icon: check
          features:
            - "Si rifuta di mangiare (disturbi alimentari)"
            - "Si gratta senza apparente motivo"
            - "Fa feci poco formate (senza che sia in corso una patologia)"
            - "Ha il pelo brutto"
            - "Manifesta comportamenti psicofisici anomali"
          # Upload image to `assets/media/` and reference the filename here
          image: features-2.png
          button:
            text: Scopri come aiutarlo!
            url: https://www.teambranco.com/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Fra Corbo"
          role: "Fancazzista"
          # Upload image to `assets/media/` and reference the filename here
          image: "features-1.png"
          text: "Grazie ai consigli nutrizionali, il mio cane è più energico e in salute che mai. Consiglio assolutamente!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Scopri il piano alimentare perfetto per il tuo cane oggi stesso!
      text: Ogni cane merita una dieta su misura per una vita sana e felice.
      button:
        text: Prenota una consulenza gratuita!
        url: https://wa.me/393476780938
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---