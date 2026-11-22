# Registro da semana 1

Período: 17/11 a 23/11/2026. Entrega: Experimentos 1 a 3 e Registros 1 a 3.
Notebook: [boatos_em_rede_semana_1.ipynb](boatos_em_rede_semana_1.ipynb)

## O que foi feito

- Montamos o modelo base: 300 eleitores em uma rede social, com os estados suscetível, espalhador e cético.
- Experimento 1: rodamos o boato na rede sem escala com sementes diferentes.
- Experimento 2: comparamos três tipos de rede (50 simulações por cenário).
- Experimento 3: comparamos o boato começando em pessoas comuns e em influenciadores.
- Respondemos os Registros 1, 2 e 3 com os números das tabelas.

## Resultados

**Experimento 1 (rede sem escala, 60 rodadas).** Alcance final por semente, de 1 a 8: 62,0%, 54,7%, 74,3%, 48,3%, 63,0%, 68,7%, 54,3% e 73,7%.

**Experimento 2 (tipo de rede).**

| Rede | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Aleatória | 58,3 | 13,8 | 9,3 | 28 | 0 |
| Mundo pequeno | 21,8 | 11,4 | 3,3 | 17 | 20 |
| Sem escala | 59,6 | 12,7 | 14,6 | 18 | 2 |

O boato chegou mais longe nas redes sem escala e aleatória (diferença menor que o desvio padrão). A rede de mundo pequeno segurou bem mais o boato.

**Experimento 3 (onde o boato começa).**

| Início | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Pessoas comuns | 59,6 | 12,7 | 14,6 | 18 | 2 |
| Influenciadores | 59,8 | 7,1 | 16,3 | 11 | 0 |

O alcance final quase não mudou, mas com influenciadores o pico veio 7 rodadas antes e o resultado ficou mais previsível.

## Estado do repositório

- Notebook da semana 1 salvo em `semana-1`.
- README com a equipe, as matrículas e o cronograma atualizado.
- Próxima semana (24/11 a 30/11): TODO 1 e 2, Experimentos 4 e 5 e Registros 4 e 5.
