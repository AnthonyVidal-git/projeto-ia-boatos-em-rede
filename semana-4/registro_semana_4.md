# Registro da semana 4

Período: 08/12 a 14/12/2026. Entrega: questões D1 a D6 (parte discursiva) e teste de código da D6.
Notebook completo, executado (semanas 1 a 4): [boatos_em_rede_semana_1.ipynb](../semana-1/boatos_em_rede_semana_1.ipynb)
Esta parte foi concluída antes do período, em 22/11/2026.

## O que foi feito

- D1: qual intervenção, sozinha, mais reduziu o alcance (letramento com 90% e checagem de 20% ficaram empatadas).
- D2: rede e influenciadores, ligados ao caso de Guarujá e ao estudo do MIT.
- D3: duas notícias comparadas com o modelo (WhatsApp e enchentes no RS).
- D4: quatro limitações do modelo, com um trecho de código para incluir uma delas.
- D5: proposta de solução (Proposta C) e argumento contra ela.
- D6: o papel da IA, com teste de código sobre um boato mais convincente (deepfake).
- O notebook foi executado do início ao fim sem erros, e os números do texto conferem com as tabelas.

## Resultados

**Teste da D6 (50 simulações por cenário).**

| Cenário | Alcance final médio (%) | Desvio padrão | Pico de espalhadores (%) | Rodada do pico | Boato morreu cedo (%) |
| --- | --- | --- | --- | --- | --- |
| Boato comum (prob_acreditar = 0,5) | 60,5 | 10,6 | 14,3 | 17 | 2 |
| Deepfake convincente (prob_acreditar = 0,8) | 80,5 | 4,1 | 27,8 | 14 | 0 |
| Deepfake + Proposta A | 54,6 | 14,0 | 13,4 | 14 | 6 |

Um boato mais convincente chega a mais gente (20 pontos a mais) e de forma mais previsível. A Proposta A, que cortava o boato comum pela metade, deixa o deepfake quase tão alcançado quanto um boato comum sem defesa.

## Estado do repositório

- Registros das semanas 1 a 4 salvos, cada um na sua pasta.
- README com a equipe, as matrículas, o cronograma e o histórico.
- Falta apenas enviar o link do repositório no ambiente da disciplina.
