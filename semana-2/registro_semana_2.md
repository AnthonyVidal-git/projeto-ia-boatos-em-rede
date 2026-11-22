# Registro da semana 2

Período: 24/11 a 30/11/2026. Entrega: TODO 1 e 2, Experimentos 4 e 5 e Registros 4 e 5.
Notebook completo (semanas 1 a 4): [boatos_em_rede_semana_1.ipynb](../semana-1/boatos_em_rede_semana_1.ipynb)
Esta parte foi concluída antes do período, em 22/11/2026.

## O que foi feito

- TODO 1: função `checar_fatos`. A verificação deu ✅ (com `prob_checagem = 0.3`, o agente checou em 31% das vezes).
- TODO 2: função `escolher_destinatarios` com o limite de encaminhamento. A verificação deu ✅ (o eleitor mais conectado tem 48 contatos e, com limite 2, enviou para 2).
- Experimento 4: quanto de checagem é preciso.
- Experimento 5: o limite de encaminhamento, comparado ao caso do WhatsApp.
- Respondemos os Registros 4 e 5 com os números das tabelas.

## Resultados

**Experimento 4 (checagem de fatos, 50 simulações por cenário).**

| Cenário | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Sem checagem | 60,5 | 10,6 | 14,3 | 17 | 2 |
| Checagem de 5% | 35,1 | 20,1 | 6,5 | 19 | 22 |
| Checagem de 10% | 22,0 | 16,3 | 3,2 | 19 | 36 |
| Checagem de 20% | 7,5 | 7,2 | 1,7 | 0 | 78 |

O efeito não é proporcional: os primeiros 5% de checagem já cortam 25,4 pontos de alcance.

**Experimento 5 (limite de encaminhamento).**

| Cenário | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Sem limite | 60,5 | 10,6 | 14,3 | 17 | 2 |
| Limite 5 | 58,1 | 10,6 | 14,2 | 18 | 2 |
| Limite 3 | 55,2 | 9,3 | 11,2 | 21 | 2 |
| Limite 1 | 21,6 | 12,2 | 3,3 | 20 | 22 |

Limites moderados (5 e 3) ajudam pouco. O limite 1 reduz o alcance em 64%.

## Estado do repositório

- Registros das semanas 1 e 2 salvos, cada um na sua pasta.
- README com o cronograma e o histórico.
- Próxima semana (01/12 a 07/12): TODO 3, Experimentos 6 e 7 e Registros 6 e 7.
