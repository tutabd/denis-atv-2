# Exercício 2: GitHub Actions - Pandoc Markdown ? PDF Slides

Este repositorio implementa um workflow de GitHub Actions que converte automaticamente \docs/presentation.md\ em slides PDF.

## Funcionalidade

O workflow é acionado por qualquer \push\ que modifique arquivos na pasta \docs/\.

Ele usa \pandoc\ e \	exlive-beamer\ para gerar os slides e publica o \slides.pdf\ resultante como um artefato na aba "Actions".
