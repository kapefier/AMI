---
layout: post
title: Effect Size Correction
subtitle: Correggere l'effect size in una meta-analisi.
gh-repo: kapefier/AMI
gh-badge: [star, fork, follow]
tags: [R, Effect Size, Meta-Analisys]
comments: true
---

------------------------------------------------------------------------

### Per quale motivo durante una meta-analisi, uno dei temi principali è la correzione della dimensione dell'effetto?

Perché non solo, come noto, l'effect size stimato $\hat\theta_k$ devia dall'effect size reale $\hat\theta$ di una misura pari all'errore di campionamento $\epsilon_k$. Se fosse questo l'unico problema da affrontare, basterebbe contenere $\epsilon_k$ per ottenere stime affidabili di $\theta$.

Invece, anche per $\epsilon_k$ tendente a 0, la stima della dimensione dell'effetto $\hat\theta_k$ può essere gravata da errori sistematici, **bias**.

Qui di seguito esploriamo le [tecniche di correzione dell'effect size]({{ '/metanalisysR.html' \| relative_url }}).
