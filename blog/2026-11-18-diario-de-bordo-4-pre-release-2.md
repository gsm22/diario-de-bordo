---
title: "Diário de bordo 4 - Pré-release 2 - 18/11/2026"
authors: Gabriel Silva Mendonça
tags: [pre-release-2]
date: 2026-11-18
---

## Compare como você está se sentindo na preparação desta segunda entrega com a forma como se sentiu na primeira.

Na primeira entrega eu me senti no meio de uma correria, porque muita coisa foi fechada de uma vez e várias pessoas abriram pull requests ao mesmo tempo. Agora o sentimento é diferente. Estou mais seguro, porque o site já está no ar em avaliaunb.com.br, o grupo passou a organizar as issues em sprints e épicos e eu sei melhor o que falta. Em compensação, sinto mais pressão com o prazo, porque o grupo ficou atrasado nas sprints e isso me fez cancelar algumas issues de segurança que davam muito trabalho para a reta final. O que eu percebi é que a pressão pesa menos quando eu sei exatamente o que está pendente, e por isso quero manter os épicos e as sprints atualizados até o fim.

## Descreva como as decisões técnicas estão sendo tomadas na sua equipe nesta fase — quem decide, como se chega a um consenso.

Nesta fase as decisões têm sido tomadas de um jeito misto. Algumas o grupo decidiu junto, como trocar o SQLite pelo Supabase, e outras ficaram com quem assumiu a parte, como o login com Google que o Caio implementou. Um caso foi os comentarios na qual eu precisava fechar onze decisões sobre como eles iam funcionar, então decidi eu mesmo, documentei tudo em um pull request e deixei aberto para o grupo confirmar. Depois, em uma reunião, o grupo mudou duas coisas que eu tinha pensado.

## Que lacunas técnicas ainda te incomodam, e o que você tem feito, ou pretende fazer, a respeito?

O que mais me incomoda é não ter certeza de que o que eu faço funciona em todos os casos, e não só nos que eu lembrei de testar. Em várias partes do projeto, como no filtro dos comentários, sempre sobrou alguma coisa que eu não previ, e sozinho eu não consigo pensar em tudo. Então tenho escrito testes para o que eu mexo, deixado as limitações anotadas na documentação e pedido para os colegas revisarem antes do merge. Agora que o site está no ar para a turma, quero ficar de olho no uso de verdade para ver o que ainda escapa.
