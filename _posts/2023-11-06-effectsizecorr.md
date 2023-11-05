---
layout: post
title: Effect Size Correction
subtitle: Correggere la dimensione dell'effetto in una meta-analisi.
gh-repo: kapefier/AMI
gh-badge: [star, fork, follow]
tags: [R, Effect Size, Meta-Analisys]
comments: true
---

------------------------------------------------------------------------

### Per quale motivo un elemento fondamentale in tema di meta-analisi è la correzione dell'effect size?

Perché non solo, come noto, l'effect size stimato $\hat\theta_k$ devia dall'effect size reale $\hat\theta$ di una misura pari all'errore di campionamento $\epsilon_k$. Se fosse questo l'unico problema da affrontare, basterebbe contenere $\epsilon_k$ per ottenere stime affidabili di $\theta$.

Invece, anche per $\epsilon_k$ tendente a 0, la stima della dimensione dell'effetto $\hat\theta_k$ può essere gravata da errori sistematici, **bias**.

Qui di seguito esploriamo le [tecniche di correzione dell'effect size]({{ '/effectsizecor.html' \| relative_url }}).
