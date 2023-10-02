# Atualizando o sistema conversacional: Aprendizado Contínuo em Chatbots.
<center>
Abner S. Barbosa,2023
</center>

## 1. Introdução

<p>Os Chatbots são verdadeiras maravilhas da tecnologia, combinando inteligência artificial e interação humano-computador de forma brilhante. Através do uso do Processamento de Linguagem Natural e análise de sentimentos, esses programas conseguem comunicar-se de maneira quase humana.</p>
<p>O aprendizado contínuo nesse cenário é bastante semelhante ao processo humano de aprendizado "auto-supervisionado", onde não é necessário possuir dados de treinamento previamente anotados ou rotulados. Ao contrário, é adquirido de forma iterativa por meio da interação com uma variedade de pessoas [2]. Para os chatbots, esse aprendizado em evolução ao longo do tempo é vital para que possam desempenhar suas funções com eficiência.</p>
<p>No entanto, é crucial ressaltar um dos grandes desafios no avanço e implementação do Aprendizado Contínuo em Aprendizado de Máquina: o temido *Concept Drift*. Esse fenômeno descreve mudanças imprevisíveis nos dados ao longo do tempo, resultando em propriedades estatísticas da variável alvo, que o modelo está tentando prever, assumindo formas inesperadas [3]. Como resultado, a eficiência e precisão dos modelos diminuem consideravelmente.</p>

## 2. Solução Proposta

<p>Diante dessa aliança estratégica, vários estudos na comunidade acadêmica vêm ganhando destaque. Um exemplo notável é o estudo de referência [4], que estabelece um conjunto diversificado de dados e métricas. Estes estão baseados na exploração de metodologias voltadas para o aprendizado contínuo de um modelo de linguagem (LM) em constante evolução, visando solucionar a desafiadora questão do Concept Drift.</p>

<p>Nesse contexto, o presente trabalho propõe uma arquitetura inovadora que integra e aplica de maneira eficaz o aprendizado contínuo em chatbots. Isso implica na integração com um sistema de busca altamente avançado e na otimização do banco de dados de referência utilizado pela inteligência artificial da aplicação. O objetivo é ampliar significativamente a capacidade de aprendizado e adaptação dos chatbots, capacitando-os a fornecer respostas mais precisas e atualizadas aos usuários.</p>

<br>
<p align="center">
    Figura 1 - Arquitetura de chatbot com aprendizado contínuo.
    <img src='./arquitetura_v2.png'alt='Arquitetura de chatbot com aprendizado contínuo'>
</p>


<p>No âmbito da arquitetura proposta, ressalta-se a abrangência de toda a aplicação implementada em um dos projetos mais recentes. No entanto, nossa atenção está especialmente voltada à essência do modelo, neste caso, o Word2Vec. Nessa concepção, o modelo é constantemente enriquecido com uma base de dados atualizada pelo serviço da IBM, o Watson - crawler. Esse serviço guarda semelhanças com um algoritmo de web scraping, mas já incorpora várias transformações e formatação de dados. Esse processo simplifica a realimentação contínua com novos dados.</p>

<p>A seleção desses dados é feita de forma criteriosa, alinhada com os contextos de aplicação do modelo. Isso ocorre por razões de curadoria e, igualmente significativo, para evitar que o modelo se torne excessivamente genérico. Se o modelo for treinado com uma base de dados que abarque todo o universo, há o risco de fornecer respostas excessivamente abstratas, o que dificulta o controle preciso das respostas destinadas aos usuários finais.</p>

## 3 Conclusão

<p>O desenvolvimento e aprimoramento contínuo de chatbots representam uma necessidade urgente e estratégica diante da rápida evolução da tecnologia e das crescentes demandas dos usuários. Neste estudo, exploramos a implementação do aprendizado contínuo em chatbots, visando melhorar sua capacidade de fornecer respostas precisas e contextualmente relevantes ao longo do tempo.</p>

<p>Destacamos a relevância do aprendizado contínuo no contexto dos chatbots, proporcionando uma abordagem dinâmica e adaptativa. Ao incorporar o conceito de *Concept Drift*, enfrentamos o desafio de lidar com mudanças imprevisíveis nos dados ao longo do tempo. A integração do serviço IBM Watson - crawler, enriquecendo o modelo Word2Vec com dados específicos e relevantes, se mostrou promissora para mitigar essas flutuações e manter a eficácia do modelo.</p>
<p>A arquitetura proposta, apresentada na Figura 1, oferece um vislumbre do futuro dos chatbots, onde a aprendizagem contínua é uma pedra angular. A integração de um sistema de busca avançado e a otimização do banco de dados de referência prometem ampliar a inteligência artificial dos chatbots, permitindo uma interação mais eficaz e enriquecedora com os usuários.</p>
<p>Em síntese, este estudo sublinha a importância do aprendizado contínuo em chatbots e propõe uma arquitetura inovadora que incorpora essa abordagem. Considerando o cenário tecnológico em constante evolução, a implementação eficaz do aprendizado contínuo se apresenta como um diferencial competitivo, capacitando os chatbots a atenderem de forma mais precisa e adaptada às necessidades dos usuários.</p>


## Referências

[1] Adamopoulou, E., & Moussiades, L. (2020). Chatbots: History, technology, and applications. Elsevier. Greece.

[2] Chen, Z., & Liu, B. (2018). Continuous Knowledge Learning in Chatbots. In Lifelong Machine Learning (pp. 131-138). Springer, Cham.

[3] Lu, J., Liu, A., Dong, F., Gu, F., Gama, J., & Zhang, G. (2019). Learning under Concept Drift: A Review. IEEE Transactions on Knowledge and Data Engineering, 31(12), 2346-2363.

[4] Jang, J., et al. (2022). Towards Continual Knowledge Learning of Language Models. arXiv:2110.03215v4.