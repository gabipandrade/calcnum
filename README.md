# Trabalhos de Cálculo Numérico

Este repositório reúne uma série de exercícios e atividades desenvolvidas para a disciplina de Cálculo Numérico. Nele, exploramos diversos tópicos, desde operações com vetores e matrizes, métodos iterativos para encontrar raízes de funções, até a resolução de redes hidráulicas e problemas avançados envolvendo interpolação, integração, diferenciação numérica, sistemas lineares e equações diferenciais.

## Integrantes do Grupo

- **Integrante 1:** Gabriela Passos de Andrade – [GitHub](https://github.com/gabipandrade)
- **Integrante 2:** Rafael Cunha Bejes Learth – [GitHub](https://github.com/RafaelLearth)
- **Integrante 3:** Barbara Fernandes Madera– [GitHub](https://github.com/barbarafernandesmadera)

## Descrição dos Trabalhos Realizados

### 1. Exercícios de Operações com Vetores e Matrizes

Os primeiros exercícios envolvem a criação de funções que geram vetores e matrizes aleatórias, aplicam combinações lineares e calculam potências de matrizes. Medimos o tempo de execução dessas operações para diferentes dimensões e utilizamos gráficos (em escala linear e log-log) para analisar a performance computacional.  
*Exemplo:* Cálculo do vetor **c** dado por _c = αa + βb_ e computação da m-ésima potência de uma matriz.

### 2. Resolução de Redes Hidráulicas

Nesta parte, foram desenvolvidos exercícios que simulam o comportamento de redes tipo grade. Os trabalhos envolveram:  
- **Montagem e resolução da rede:** Construção de funções que recebem os parâmetros da rede (como pressões fixas em pontos específicos, fontes e consumos) e retornam os vetores de pressão e fluxo.  
- **Cálculo dos escoamentos e potência:** A partir da matriz de condutâncias, os exercícios envolvem o cálculo do fluxo pelos canos e a potência consumida pelas bombas, utilizando conceitos de álgebra linear.  
- **Estudos comparativos:** Foram realizados testes variando as conexões e os parâmetros da rede para analisar o comportamento da pressão e da vazão.  

### 3. Métodos Numéricos Avançados e Análise de Sistemas

Outra parte dos trabalhos foca em métodos numéricos para resolução de problemas não lineares e sistemas lineares, incluindo:  
- **Método de Newton:** Implementação de uma função geral para encontrar zeros de funções, com opção para usar derivada analítica ou aproximação numérica.  
- **Sistemas Lineares e Fatoração de Matrizes:** Análise da resolução de sistemas usando tanto matrizes densas quanto esparsas, e estudo da fatoração de Cholesky para matrizes definidas positivas.  
- **Interpolação, Integração e Diferenciação:** Desenvolvimento de scripts para interpolar funções, aplicar regras de quadratura para integração numérica e diferenciar funções, comparando métodos globais e por partes.  
- **Equações Diferenciais Ordinárias (EDOs) e Problemas de Autovalores:** Modelagem e resolução numérica de EDOs, além da análise de modos de oscilação e autovalores/autovetores em problemas mecânicos e de redes hidráulicas.

### 4. Testes e Visualizações Gráficas

Cada exercício foi acompanhado por testes práticos e diversas visualizações gráficas, utilizando a biblioteca Matplotlib. Os gráficos gerados ajudam a compreender a evolução dos métodos iterativos, a distribuição dos escoamentos em redes e a precisão das aproximações numéricas adotadas.

## Conclusão

Os trabalhos deste repositório demonstram a aplicação prática dos conceitos teóricos de Cálculo Numérico em problemas reais e simulados. Através da implementação dos métodos em Python e da análise dos resultados gráficos, foi possível compreender as vantagens e limitações de cada abordagem numérica, contribuindo para uma aprendizagem aprofundada da disciplina.

Em caso de dúvidas ou para mais informações sobre os métodos implementados, sinta-se à vontade para entrar em contato com os integrantes do grupo.
