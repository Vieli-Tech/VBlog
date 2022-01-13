---
title: Preços
layout: page
permalink: "/precos/"
---

<div style="font-size:16px;line-height:1;text-align:center;width:100%">
  <p> 
    <span style="color:rgb(0, 0, 0);font-size: 11pt">
      A fim de mantermos a qualidade de serviços prestados e ter disponível uma equipe qualificada para dar manutenção, assistência técnica e melhorias para o sistema de apontamento VieliTech, foi atualizada a política de valores conforme o tipo de solicitação e atuação por parte da VieliTech.
    </span>
  </p>
</div>
<div>
  <table style="border: 1px solid black;">
    <thead>
      <tr style="border: 1px solid black;">
        <td style="border: 1px solid black;text-align: center;font-weight: bold;" rowspan="6">Custos para assistência técnica e manutenção</td>
        <td style="border: 1px solid black;text-align: center;font-weight: bold;">Demanda</td>
        <td style="border: 1px solid black;text-align: center;font-weight: bold;">Valor/Hora</td>
      </tr>
      {% for item in site.data.tabela-precos.demandas %}
      <tr style="border: 1px solid black;">
        <td style="border: 1px solid black;">
          {{ item.descricao }}
        </td>
        <td style="border: 1px solid black;">
          {{ item.valor }}
        </td>
      </tr>
      {% endfor %}
    </thead>
  </table>
</div>
<div style="font-size:16px;line-height:1;text-align:left;width:100%">
  <p>
    <span style="color:rgb(0, 0, 0);font-size: 11pt">
      Valores e tempos de atendimento serão fechados e encaminhados com o relatório e fatura mensalmente.
    </span>
  </p>
  <p>
    <em>
      <strong>
        <span style="color:rgb(0, 0, 0);font-size: 11pt">
          <span style="text-decoration:underline;">
            Observações:
          </span>
        </span>
      </strong>
    </em>
  </p>
  <ul>
    <li>
      <p>
        <span style="color:rgb(0, 0, 0);font-size: 11pt">
          Valores são referentes para atendimento em horário comercial, de segunda a sexta-feira, das 7:30 as 17:30. Atendimentos fora do horário comercial e em feriados, terão um acréscimo de 50%
        </span>
      </p>
    </li>
    <li>
      <p>
        <span style="color:rgb(0, 0, 0);font-size: 11pt">
          Para atendimento presencial, os valores de hora técnica são individuais e serão cobrados sempre no mínimo 4 horas de trabalho, independente da utilização das mesmas.
        </span>
      </p>
    </li>
    <li>
      <p>
        <span style="color:rgb(0, 0, 0);font-size: 11pt">
          Para emissão de reembolso e hospedagem, será acrescentado 10% no valor da Nota Fiscal gerada.
        </span>
      </p>
    </li>
    <li>
      <p>
        <span style="color:rgb(0, 0, 0);font-size: 11pt">
          Despesas de alimentação, hospedagem, deslocamento e passagens terrestres ou aéreas, correm por conta do cliente.
        </span>
      </p>
    </li>
  </ul>
</div>
