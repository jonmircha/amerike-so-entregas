---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Información de la materia
publishDate: 31 Mar 2022
name: Jonathan MirCha
description: Aquí encontraras toda la información y planeación de tu materia S.O. y Redes
---

<Cool name={frontmatter.name} href="https://github.com/jonmircha" client:load />

## S.O y Redes Sociales

Hola Estudiantes!
