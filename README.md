# Airline Review Dataset

Este dataset contém avaliações de passageiros sobre diferentes companhias aéreas. Ele foi coletado a partir de um conjunto de dados de avaliações de voos e oferece uma visão detalhada da experiência do passageiro com base em várias características do voo.

## Colunas do Dataset

As colunas (ou características) no dataset são descritas a seguir:

### 1. **Airline**
- **Descrição**: O nome da companhia aérea avaliada.
- **Tipo**: Categórica (Exemplo: "Delta", "American Airlines", etc.)

### 2. **Title**
- **Descrição**: Um título ou resumo curto da avaliação.
- **Tipo**: Texto (string).

### 3. **Author**
- **Descrição**: O nome do revisor.
- **Tipo**: Texto (string).

### 4. **Country**
- **Descrição**: O país de onde o revisor é originário.
- **Tipo**: Categórica (Exemplo: "United States", "Brazil", etc.)

### 5. **Date**
- **Descrição**: A data em que a avaliação foi postada.
- **Tipo**: Data (Exemplo: "2021-05-14").

### 6. **Verified**
- **Descrição**: Indica se a avaliação é verificada (TRUE/FALSE).
- **Tipo**: Categórica (Valores possíveis: "TRUE", "FALSE").

### 7. **Review**
- **Descrição**: Texto completo da avaliação, que geralmente inclui opiniões detalhadas sobre a experiência de voo.
- **Tipo**: Texto (string).

### 8. **Type Of Traveller**
- **Descrição**: O tipo de viajante, como se estava viajando sozinho, em casal, a negócios, etc.
- **Tipo**: Categórica (Exemplo: "Solo", "Couple", "Business", etc.)

### 9. **Seat Type**
- **Descrição**: A classe do assento, como Econômica, Executiva, etc.
- **Tipo**: Categórica (Exemplo: "Economy", "Business", etc.)

### 10. **Route**
- **Descrição**: A rota do voo (exemplo: Moroni para Moheli).
- **Tipo**: Texto (string) que descreve a origem e o destino.

### 11. **Date Flown**
- **Descrição**: A data em que o voo ocorreu.
- **Tipo**: Data (Exemplo: "2021-05-12").

### 12. **Seat Comfort**
- **Descrição**: Avaliação de conforto do assento (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 13. **Cabin Staff Service**
- **Descrição**: Avaliação do serviço da tripulação de cabine (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 14. **Food & Beverages**
- **Descrição**: Avaliação das refeições e bebidas a bordo (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 15. **Inflight Entertainment**
- **Descrição**: Avaliação da entretenimento durante o voo (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 16. **Ground Service**
- **Descrição**: Avaliação dos serviços no aeroporto (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 17. **Wifi & Connectivity**
- **Descrição**: Avaliação da qualidade e disponibilidade do Wi-Fi (nota de 1 a 5, caso aplicável).
- **Tipo**: Numérica (Escala de 1 a 5).

### 18. **Value For Money**
- **Descrição**: Avaliação de valor pelo dinheiro, ou seja, se o voo valeu o preço pago (nota de 1 a 5).
- **Tipo**: Numérica (Escala de 1 a 5).

### 19. **Recommended**
- **Descrição**: Indica se o passageiro recomendaria a companhia aérea (sim/não).
- **Tipo**: Categórica (Valores possíveis: "Yes", "No").

### 20. **Aircraft**
- **Descrição**: Modelo da aeronave utilizada no voo (quando mencionado).
- **Tipo**: Texto (string).

## Objetivo do Dataset

O objetivo deste dataset é analisar a satisfação dos passageiros com base em diversas características do voo. As informações contidas nele podem ser usadas para:
- Análise de sentimentos.
- Identificação de aspectos fortes e fracos das companhias aéreas.
- Classificação e previsão de recomendações com base nas características do voo.
- Análise de tendências ao longo do tempo, identificando se as companhias aéreas estão melhorando ou piorando.

## Possíveis Análises

Com esse dataset, é possível realizar análises como:
- **Análise de Sentimentos**: Usar o texto das avaliações para categorizar as avaliações como positivas, negativas ou neutras.
- **Análise de Tópicos**: Extrair tópicos comuns das avaliações usando técnicas de NLP.
- **Comparações entre companhias aéreas**: Comparar a performance de diferentes companhias aéreas em termos de satisfação do cliente.
- **Análise de Padrões de Satisfação**: Investigar a relação entre diferentes variáveis (como conforto do assento, serviço da tripulação, etc.) e a satisfação geral do cliente.
- **Visualizações**: Gerar gráficos de dispersão, histogramas e gráficos de barras para entender a distribuição das notas e comparar variáveis.


