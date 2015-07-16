---
title: Article template
tags:
  - Blog
description: >
    Guidelines to post creation, verbatim. Use punctuation!
---

Lavoro in Deloitte e il firewall non mi fa passare dalla porta 22

la cosa è curiosa, perchè sto facendo un server per un progetto interno, ma, per motivi burocratrici ho dovuto usare un altro dominio
che non è trusted
quelli del support non ti danno supporto :)

allora ho creato un server in cloud e ho messo ssh sulla porta 443, che si suppone il firewall non blocchi, visto che è l'https

poi PuTTY va configurato per poter passare dal firewall, e funziona

## Section

All sections start with an **h2**.

<div class="alert alert-info">This is an alert</div>

This is a <span class="label label-default">label</span>

## See also

* [article]({% post_url yyyy-mm-dd-article %})

## References

[ref1][1]

  [1]: http://link.com/ "link"

