# Registro da semana 3

Período: 01/12 a 07/12/2026. Entrega: TODO 3, Experimentos 6 e 7 e Registros 6 e 7.
Notebook: [boatos_em_rede_semana_3.ipynb](boatos_em_rede_semana_3.ipynb) (completo, semanas 1 a 4, executado)
Esta parte foi concluída antes do período, em 22/11/2026.

## O que foi feito

- TODO 3: função `receber_boato` com o letramento midiático. A verificação deu ✅ (o eleitor letrado resistiu e o comum acreditou).
- Experimento 6: quanta educação midiática é preciso.
- Experimento 7: a proposta da equipe, com orçamento de 15 pontos. Testamos três propostas (A, B e C), todas dentro do orçamento.
- Respondemos os Registros 6 e 7 com os números das tabelas.

## Resultados

**Experimento 6 (letramento midiático, 50 simulações por cenário).**

| Cenário | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Ninguém letrado | 60,5 | 10,6 | 14,3 | 17 | 2 |
| 30% letrados | 38,0 | 14,7 | 7,1 | 24 | 8 |
| 60% letrados | 18,1 | 13,8 | 2,8 | 19 | 42 |
| 90% letrados | 6,3 | 5,4 | 1,7 | 0 | 78 |

**Experimento 7 (propostas dentro de 15 pontos).**

| Proposta | Custo | Alcance final médio (%) | Com influenciadores (%) |
| --- | --- | --- | --- |
| Sem intervenção | 0 | 60,5 | 59,9 |
| A: checagem 5%, limite 5, 20% letrados | 10 | 27,4 | 32,7 |
| B: sem checagem, limite 3, 30% letrados | 9 | 25,4 | 36,5 |
| C: checagem 10%, limite 5, 10% letrados | 13 | 17,2 | 26,1 |

A equipe escolheu a Proposta C: menor alcance, e 40% das simulações com o boato morto cedo. Quando o boato começa em influenciadores, o efeito diminui, mas ela continua a melhor.

## Estado do repositório

- Registros das semanas 1, 2 e 3 salvos, cada um na sua pasta.
- README com o cronograma e o histórico.
- Próxima semana (08/12 a 14/12): questões D1 a D6 e teste de código da D6.
