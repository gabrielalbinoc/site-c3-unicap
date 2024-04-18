---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Bem vindo ao  site de Ciência da Computação
        content: Fique por dentro das novidades do curso
        align: center
        background:
          image:
          #A IMAGEM DEVE ESTAR DENTRO DO FOLDER/PASTA assets /media  
            filename: code.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 💡 Projetos de extensão e Iniciaçao Científica
        content: 'Aprenda com nossas postagem e fique por dentro dos eventos'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title:  😎 Veja mais sobre o nosso curso
        content: 'Início das aulas na Segunda Semana de Fevereiro'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---