---
# CIDES - Home Page Oficial
title: "CIDES (Grupo de Divulgación
Científica))"
type: landing

sections:
  # 1. REDACCIONES CIENTÍFICAS (Versión Estable)
  - block: collection
    id: redacciones
    content:
      title: ""
      filters:
        folders:
          - post
        featured_only: false
        exclude_featured: false
      count: 5
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: slider
      columns: '1'
      item_height: '650px'
      overlay:
        darken: 0.6
      background:
        apply_to_item: true
      item:
        text:
          align: center
      spacing:
        padding: ['0', '0', '0', '0']
      # Línea azul oscura divisoria
      css_style: 'border-bottom: 8px solid #1a2a4a;'

  # 2. TALLERES Y EVENTOS (Dosis de Ciencia)
  - block: collection
    id: eventos
    content:
      title: "Dosis de Ciencia"
      subtitle: "Talleres y Eventos Presenciales"
      filters:
        folders:
          - eventos
    design:
      columns: '2'
      view: card
      spacing:
        padding: ['60px', '0', '60px', '0']
      css_style: 'border-bottom: 8px solid #1a2a4a;'

  # 3. PODCAST (Aceite de Inmersión)
  - block: markdown
    id: podcast
    content:
      title: ""
      text: |
        <div style="background: linear-gradient(135deg, #000000 0%, #1db954 100%); padding: 45px; border-radius: 20px; color: white; text-align: center; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
          
          <h4 style="color: #1db954; text-transform: uppercase; letter-spacing: 3px; margin: 0; font-size: 0.9rem;">Podcast Científico</h4>
          <h1 style="font-size: 2.8rem; margin: 10px 0 20px 0; line-height: 1.1; font-weight: 800; color: white; letter-spacing: -1px;">ACEITE DE INMERSIÓN</h1>
          
          <p style="font-size: 1.1rem; line-height: 1.6; color: #f0f0f0; max-width: 800px; margin: 0 auto 30px auto; font-weight: 300;">
            Hablaremos de temas de actualidad mundial, análisis de artículos y actualidad científica peruana. Entrevistas, humor científico, investigaciones de biólogos cusqueños y noticias curiosas en un formato fresco e innovador al servicio de la comunidad científica. <strong>¡Sumérgete con nosotros!</strong>
          </p>
          
          <div style="margin: 25px 0;">
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/show/6nhAUpY7qoqBKxo6czHmdj?utm_source=generator" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
          </div>

          <div style="margin-top: 25px;">
            <a href="https://open.spotify.com/embed/show/6nhAUpY7qoqBKxo6czHmdj?utm_source=generator" target="_blank" style="background-color: #1db954; color: black; padding: 14px 40px; border-radius: 30px; text-decoration: none; font-weight: bold; display: inline-block; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">
              Escuchar en Spotify
            </a>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['80px', '0', '80px', '0']
      css_style: 'border-bottom: 8px solid #1a2a4a;'

  # 4. SECCIÓN DE CONTACTO
  - block: contact
    id: contacto
    content:
      title: "Únete a CIDES"
      subtitle: "¿Quieres colaborar?"
      text: "Escríbenos para formar parte del círculo de divulgación científica en Cusco."
      email: "cides.divulgacion@gmail.com"
    design:
      columns: '2'
      background:
        color: '#1a2a4a'
        text_color_light: true
---