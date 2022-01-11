---
title: Perguntas dos Usuários!
layout: post
date: '2022-01-11 07:00:00 -0300'
categories:
- vielitech
- FAQ
image: https://avatars.githubusercontent.com/u/72389266?s=96&v=4
excerpt: Nesse post vamos trazer 5 perguntas que recebemos essa semana e que podem também te ajudar
---

![alt_text](https://avatars.githubusercontent.com/u/72389266?s=96&v=4)

Nesse post vamos trazer 5 perguntas que recebemos essa semana e que podem também te ajudar

:monoculos_face:

1 – Quando finalizado o Setup, na tela principal do totem,  o sistema gera uma parada como as demais?

O Botão de setup na tela principa do Toteml, uma vez acionado, ele aciona a parada, não conta a produção, porém libera a esteira do equipamento para possibilitar testes de prototipos e regulagens. Ele so volta a contabilizar a produção após a finalização

2 – Como é calculada a meta do dia?

Meta = tempo total disponível * meta hora. 

A meta hora voce verifica no painel de configurações,  IPSERVIDOR:8082

3  - Quando o indicador sai do vermelho e vai para o amarelo? Qual é o parâmetro?

Tambem voce edita as faixas e limites das cores no painel de configuração… cada equipamento tem o seu % para vermelho amarelo e verde para cada indicador: disposição, perf, qualidade,  (oee é calculado automaticamente), meta e retrabalho

4 – Qual a diferença dos indicadores de Ritmo no telão?

ATUAL: quanto produziu nos últimos 60 segundos… as cores dele se referem à capacidade máxima do  equipamento, ou seja, quando está verde é porque está produzindo sua capacidade máxima

DIA: é o produzido no dia dividido pelo tempo disponível, em minutos

META: meta hora do equipamento dividido por 60

5 - Queremos mostrar na tela apenas as máquinas do setor da usinagem, consigo fazer?

Sim, voce pode criar diversos grupos e colocar os equipamentos que quiser em cada um deles…

Para isso primeiro cria o nome do grupo no painel de configurações

Depois no painel de configurações vá em equipamentos e acesse um por um dos equipamentos para incluir nos grupos que voce quer

Depois disso feito voce pode ver grupos de diferentes formas, conforme os links abaixo:

IPSERVIDOR:8080/#/grupos/1   >>>>> carrossel das telas dos equipamentos do grupo, trocando o equipamento a cada 15 segundos

IPSERVIDOR:8080/#/dashboard/1   >>>>> terá um resumo dos equipamentos na rela

IPSERVIDOR:8080/#/gruposTotais/1   >>>>> soma da produção e metas de todos equipamentos do grupo para ter uma visão geral do grupo… essa feature é interessante se tiver grupos por tipo de máquinas, juntando as semelhantes

 

Obrigado
