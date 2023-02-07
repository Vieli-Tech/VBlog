---
title: Usando os Grupos
layout: post
date: '2022-01-14 07:00:00 -0300'
categories:
- vielitech
- Grupos
- configuracao 
excerpt: Descubra os benefícios de usar os Grupos de equipamentos e aprenda como cadastrar e usar-los
---
 
## Utilizando grupos para facilitar gestão

Foi implementando recentemente melhorias na organização e visualização de grupos. Hoje, o sistema de apontamento da VieliTech tem o portal de configurações (IPSERVIDOR:8082), facilmente você consegue criar novos grupos e incluir equipamentos nos grupos.

No portal, abra o menu lateral, e clica em  <em>**Configurações**</em> e abrirá algumas opções, sendo uma delas <em>**Grupos**</em>, selecione. Aparecerá a lista de Grupos existente, você pode editar os nomes dele, clicando no lápis à direita do nome, ou apertando no sinal de  <em>**+**</em>, abrirá um formulário para criar um novo, digite o nome e salve. Para saber o número do ID dos grupos, seleciona o modo de edição do grupo na lista e clique na URL do navegador e aparecerá no fim do endereço o ID do grupo. Essa informação você usará para acessar aos painéis de acompanhamento em tempo real dos indicadores dos grupos.
Depois de criado o grupo, você ainda precisa incluir os equipamentos que compõem o grupo. Para isso, no Menu lateral do portal de configurações, clique em  <em>**Equipamentos**</em>. Na lista de equipamentos que aparecerá, selecione o equipamento, clicando em cima do nome, e role a tela até onde aparecer <em> Grupos</em>, onde apresentará todos os Grupos criados. Selecione os grupos que queira que o equipamento apareça, salve e pronto! 
Feito isso, você pode utilizar os grupos da seguinte maneira:

 - **Carrossel dos equipamentos**: IPSERVER:8080/#/grupos/(numero do grupo) irá aparecer em rodízio as telas dos equipamentos do grupo, trocando o equipamento a cada 15 segundos]
 
 - **Resumo dos indicadores do Grupo**: IPSERVER:8080/#/grupoTotal/(numero do grupo) Irá aparecer uma tela só com o resumo de todos os indicadores dos equipamentos do grupo agrupados. Essa função é interessante se tiver grupos por tipo de máquinas, juntando as semelhantes do mesmo setor, para ver os indicadores do ser.
 Para ver varios grupos em formato de carrossel acesse  IPSERVER:8080/#/gruposTotais?grupos=(numero dos grupos separado por virgula)
  
  - **Vários equipamentos na mesma tela** IPSERVER:8080/#/dashboard/(numero do grupo) Até 9 equipamentos na tela com o resumo da produção, meta e OEE do equipamento.
