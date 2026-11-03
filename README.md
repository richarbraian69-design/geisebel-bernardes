# Dashboard de Metas (Dra. Geise Bel)

Painel visual das metas de faturamento com harmonização facial. Todos os números são ajustáveis na própria tela, e a projeção recalcula na hora.

## O que o painel mostra

- **Projeção de faturamento** e quanto falta (ou sobra) para a meta do mês
- **Ritmo necessário**: leads por dia, agendamentos, procedimentos, CAC e ROAS
- **Engrenagem da meta**: o valor que cada alavanca precisaria marcar sozinha para a meta fechar, com as outras paradas onde estão
- **Onde estamos agora**: quanto já foi faturado, quanto falta e o ritmo diário necessário
- **Bônus da equipe**: 1% do faturamento bruto ao bater a meta

## Alavancas ajustáveis

| Controle | Para que serve |
|---|---|
| Investimento por dia | Verba de captação de leads |
| Custo por lead | A variável que mais mexe no resultado |
| Lead vira agendamento | Conversão do primeiro contato no WhatsApp |
| Consulta vira procedimento | Fechamento na consulta |
| Ticket médio | Valor médio por paciente |
| Faturamento de outras origens | Orgânico, indicação e retorno (fora do tráfego pago) |
| Meta do mês | Padrão R$ 100.000 |
| Dias de campanha | Padrão 30 |

Os ajustes ficam salvos no navegador de quem abrir (cada pessoa guarda a própria simulação).

## Cenários prontos

Os atalhos no topo carregam as taxas de meses reais:

| Cenário | CPL | Lead → agend. | Agend. → proc. |
|---|---|---|---|
| Hoje | R$ 25,16 | 5,0% | 78,8% |
| Julho | R$ 21,61 | 6,5% | 76,9% |
| Agosto | R$ 10,49 | 4,9% | 80,0% |
| Meta Nov | R$ 18,00 | 6,5% | 80,0% |
| Cenário bom | R$ 12,00 | 7,0% | 82,0% |

## Base dos números

Dados de campanha de 2026 (Meta Ads):

| Mês | Investido | Leads | CPL | Agendamentos | Procedimentos |
|---|---|---|---|---|---|
| Julho | R$ 4.343,22 | 201 | R$ 21,61 | 13 | 10 |
| Agosto | R$ 4.269,52 | 407 | R$ 10,49 | 20 | 16 |
| Outubro (parcial) | R$ 780,00 | 31 | R$ 25,16 | 3 | não informado |

Faturamento total de outubro: R$ 51.000.

## Rodar localmente

```bash
npm start
# http://localhost:3000
```

Sem dependências externas: servidor estático em Node puro.
