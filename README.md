# EnergyFusion - Plataforma de Comparação de Eletrodomésticos de Eficiência Energética

## Descrição do Projeto

O EnergyFusion é uma plataforma desenvolvida para ajudar consumidores a fazer escolhas informadas ao comparar a eficiência energética de eletrodomésticos. A plataforma fornece dados comparativos de consumo energético de aparelhos como refrigeradores, micro-ondas, lavadoras automáticas, ventiladores de mesa e de teto. Ao promover escolhas mais sustentáveis, o EnergyFusion contribui para a conscientização energética e incentiva a redução do consumo de energia.

## Descrição do Problema

Com o aumento da demanda por energia elétrica, especialmente em áreas remotas ou de difícil acesso a energia sustentável, existe uma necessidade urgente de incentivar a escolha por eletrodomésticos com maior eficiência energética. Muitos consumidores não têm acesso claro a informações sobre o impacto energético dos eletrodomésticos, o que dificulta a tomada de decisões conscientes. Esse projeto visa resolver esse problema, proporcionando uma plataforma de comparação entre produtos com base no consumo e na eficiência energética.

## Metodologia

A metodologia do projeto inclui as seguintes etapas:

1. **Coleta de Dados:** Dados de consumo e eficiência foram coletados para os principais eletrodomésticos, como refrigeradores, micro-ondas, ventiladores e lavadoras automáticas, a partir de bases de dados confiáveis e validadas.

2. **Modelagem de Dados:** Os dados foram organizados em tabelas específicas para cada categoria de eletrodoméstico, como `lavadoras_automaticas`, `micro_ondas`, `ventiladores_de_mesa`, e `ventiladores_de_teto`, além de uma tabela genérica `appliances` que centraliza os atributos comuns.

3. **Desenvolvimento da Aplicação:** A aplicação foi desenvolvida em C# e utiliza Java para a API, aproveitando o Entity Framework Core para interações com o banco de dados Oracle. A plataforma foi projetada para disponibilizar uma interface amigável com funcionalidades de comparação de produtos e cálculos de economia de energia.

4. **Modelo de Machine Learning (YOLO):** Foram usados algoritmos de visão computacional para identificar e classificar elementos nos produtos a partir de imagens. Ferramentas como Roboflow e Ultralytics Hub foram aplicadas para processar imagens e treinar modelos de classificação e detecção.

## Resultados Obtidos

Os resultados mostram uma melhoria na clareza e acessibilidade das informações sobre eficiência energética para os usuários. A plataforma permite ao consumidor:

- **Comparar Consumo Energético:** Visualizar e comparar o consumo de diversos eletrodomésticos, auxiliando na escolha de produtos mais eficientes.
- **Estimar Economia:** Calcular economias potenciais de acordo com o consumo e o custo energético.
- **Facilidade de Acesso:** A interface de fácil uso da plataforma proporciona uma experiência intuitiva e informativa.

## Conclusão

O EnergyFusion cumpre seu objetivo de facilitar decisões conscientes e informadas para os consumidores ao apresentar dados claros e comparáveis sobre a eficiência energética dos eletrodomésticos. Com uma abordagem inovadora baseada em Machine Learning e uma interface acessível, o projeto oferece um impacto positivo, promovendo o uso sustentável de energia. O próximo passo inclui expandir a base de dados para incluir mais categorias de eletrodomésticos e aprimorar o modelo de previsão para regiões com acesso limitado a energia confiável.

## Link vídeo youtube
### [Vídeo IA](https://youtu.be/qrLKZ-cRk3U)

## Integrantes
### Arthur Fenili RM 552752
### Enzo Antunes Oliveira RM 553185
### Vinicío Raphael RM 553813
