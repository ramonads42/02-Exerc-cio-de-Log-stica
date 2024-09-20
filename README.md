# Planejamento de Rotas de Entrega

# Cenário

Você é o gerente de logística de uma empresa de entregas que atende a uma cidade com vários pontos de entrega. Sua tarefa é planejar as rotas de entrega para uma frota de veículos, de forma que o tempo de viagem total e os custos operacionais sejam minimizados. Considere as seguintes informações:

# Pontos de Entrega:
    - Ponto A: 20 pacotes
    - Ponto B: 15 pacotes
    - Ponto C: 10 pacotes
    - Ponto D: 25 pacotes
 - **Capacidade dos Veículos:**  Cada veículo pode transportar até 30 pacotes por viagem.
- **Distâncias entre os Pontos de Entrega (em km):**
    - A -> B: 5 km
    - A -> C: 10 km
    - A -> D: 8 km
    - B -> C: 4 km
    - B -> D: 7 km
    - C -> D: 3 km

# Tarefas
1. **Divisão dos Pacotes:**
    - Determine como os pacotes serão divididos entre os veículos, considerando a capacidade máxima de 30 pacotes por veículo.
2. **Planejamento de Rotas:**
    - Planeje as rotas para os veículos de forma que o total de distância percorrida seja minimizado.
    - Considere que os veículos sempre retornam ao ponto de partida (Depósito) após concluir suas entregas.
3. **Cálculo do Custo:**
    - Suponha que o custo operacional é de R$ 2,00 por km. Calcule o custo total de cada rota planejada.
4. **Documentação:**
    - Escreva um relatório em Markdown que documente:
        - A divisão dos pacotes entre os veículos.
        - As rotas planejadas para cada veículo, incluindo a sequência de entregas.
        - O custo total de cada rota.
        - Qualquer desafio encontrado e como foi resolvido.

# Relatório de Otimização da Cadeia de Suprimentos

## Alocação das Demandas

- CD1:
  - Loja 1: 150 unidades (Custo: R$ 750,00)
  - Loja 3: 300 unidades (Custo: R$ 1800,00)

- CD2:
  - Loja 4: 180 unidades (Custo: R$ 810,00)
  - Loja 5: 250 unidades (Custo: R$ 1500,00)

- CD3:
  - Loja 6: 350 unidades (Custo: R$ 1925,00)
  - Loja 7: 220 unidades (Custo: R$ 880,00)

## Cálculo dos Custos Totais

- Custo Total de Transporte: R$ 7.665,00

## Simulação de Pico de Demanda

- Novo Cálculo de Demandas:
  -Loja 1: 180 unidades
  -Loja 2: 240 unidades
  -Loja 3: 360 unidades
  -Loja 4: 216 unidades
  -Loja 5: 300 unidades
  -Loja 6: 420 unidades
  -Loja 7: 264 unidades

- Resultado:
  - Capacidade do CD1 excedida em 100 unidades.
  - Loja 10 não pode ser atendida pelo CD3 devido à capacidade excedida.

## Estratégia de Expansão

- Proposta:
  - Aumentar a capacidade do CD1 em 200 unidades.
  - Custo estimado de expansão: R$ 50.000,00.
  - Benefícios: Atende ao aumento de demanda com menor custo adicional de transporte.

## Conclusão

A estratégia proposta permitirá à empresa atender ao aumento de demanda, mantendo os custos de transporte relativamente baixos.

