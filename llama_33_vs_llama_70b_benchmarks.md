---
# Tópico: Llama 3.3 70B vs Llama 3 70B
**TIPO:** Comparação de Modelos de Linguagem
**TAGS:** Llama 3.3 70B, Llama 3 70B, Meta, Modelos de Linguagem, Inteligência Artificial
**DATA_REF:** 2024/12

## Núcleo do Conhecimento
* **Llama 3.3 70B**
    * **Definição:** Modelo de linguagem de 70 bilhões de parâmetros, desenvolvido pela Meta, com desempenho comparável ao Llama 3.1 405B, mas com menor tamanho e melhor eficiência.
    * **Características:**
        + Context window de 128K tokens
        + Suporte a 8 idiomas
        + Treinado em uma mistura de dados públicos com mais de 15 trilhões de tokens
        + Data de corte de conhecimento em dezembro de 2023
    * **Benchmarks:**
        + GPQA: 50,5% (0-shot, CoT)
        + HumanEval: 88,4% (pass@1)
        + IFEval: 92,1%
        + MATH: 77% (0-shot, CoT)
        + MMLU: 86% (0-shot, CoT)
* **Llama 3 70B**
    * **Definição:** Modelo de linguagem de 70 bilhões de parâmetros, desenvolvido pela Meta, com desempenho inferior ao Llama 3.3 70B.
    * **Características:**
        + Context window de 8.000 tokens
        + Suporte a 8 idiomas
        + Treinado em uma mistura de dados públicos com mais de 15 trilhões de tokens
        + Data de corte de conhecimento em dezembro de 2023
    * **Benchmarks:**
        + MMLU: 82% (5-shot)

## Comparação de Preços
* **Llama 3.3 70B:**
    + Preço de entrada: $0,23 por milhão de tokens
    + Preço de saída: $0,40 por milhão de tokens
* **Llama 3 70B:**
    + Preço de entrada: $0,35 por milhão de tokens
    + Preço de saída: $0,40 por milhão de tokens

## Desempenho em Arm Neoverse CPUs
* **Llama 3.3 70B:**
    + Velocidade de geração de tokens: até 50 tokens por segundo
    + Velocidade de geração de tokens por lote: até 4 lotes por segundo
    + Desempenho estável em batch sizes de até 4

## Conclusão
* O Llama 3.3 70B é um modelo de linguagem mais eficiente e acessível do que o Llama 3 70B, com desempenho comparável ao Llama 3.1 405B.
* O Llama 3.3 70B é mais barato do que o Llama 3 70B, com preços de entrada e saída mais baixos.
* O desempenho do Llama 3.3 70B em Arm Neoverse CPUs é estável e eficiente, tornando-o uma opção viável para aplicações de inteligência artificial.