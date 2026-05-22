---
title: "Les générateurs de sites statiques, et si on arrêtait de se compliquer la vie "
description: Ce blog tourne sur Eleventy. Donc oui, cet article sur les générateurs de sites statiques est lui-même généré statiquement
tags: posts
date: Created
---
En ce moment à l'école, on explore des outils qu'on appelle les SSG pour Static Site Generators, ou générateurs de sites statiques en bon français. Et franchement, j'ai envie de vous en parler parce que ça m'a un peu changé la façon de voir le développement web.

## Mais c'est quoi un SSG ?
Un générateur de sites statiques, c'est un outil qui prend du contenu souvent écrit en Markdown, et des templates, et qui produit des fichiers HTML/CSS/JS tout prêts à être servis. Pas de base de données, pas de serveur qui calcule la page à chaque requête. Juste des fichiers. Simples, rapides, solides.
C'est un peu comme préparer tous ses repas de la semaine le dimanche plutôt que de cuisiner à la dernière minute chaque soir. Le résultat est là, disponible immédiatement.

## Les principaux acteurs

**Eleventy (11ty)**
C'est celui avec lequel j'ai commencé, et j'en suis plutôt contente. Eleventy est minimaliste, très flexible, et il ne vous impose rien : vous choisissez votre langage de template (Nunjucks, Liquid, Markdown...), votre structure de fichiers, votre façon de travailler. C'est parfait pour apprendre parce qu'il y a peu de magie cachée — on comprend ce qu'on fait.
Ce blog tourne d'ailleurs sur Eleventy. Meta, non ?

**Astro**
Astro est plus récent et franchement très séduisant. Sa grande force c'est l'architecture en îles (islands architecture) : vous pouvez intégrer des composants React, Vue ou Svelte uniquement là où vous en avez besoin, sans charger du JavaScript inutilement partout. Il est orienté performance dès le départ, et sa syntaxe .astro est assez intuitive quand on vient du monde des composants.

**Hugo**
Hugo c'est le vétéran de la bande. Écrit en Go, il est extrêmement rapide, on parle de milliers de pages générées en quelques secondes. Si vous avez un gros blog ou de la doc technique avec beaucoup de contenu, Hugo est probablement le bon choix. La courbe d'apprentissage est un peu plus raide, mais la communauté est solide.
Pourquoi c'est cool pour une dev en formation ?
Ce que j'aime dans les SSG, c'est qu'ils remettent le focus sur l'essentiel : le contenu et la structure. On n'est pas noyée sous des couches d'abstraction. On comprend ce qui se passe entre le fichier Markdown qu'on écrit et la page HTML qui s'affiche dans le navigateur.

Et puis déployer un site statique c'est d'une simplicité désarmante. Un dossier de fichiers à copier sur un serveur, et c'est en ligne. Ce blog en est la preuve !