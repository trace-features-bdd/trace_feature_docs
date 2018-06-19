### Histórico de Revisões

| Data | Versão | Descrição | Autor(es) |
|:----:|:------:|:---------:|:-----:|
|30/05/2018|1.0|Criação do Documento| Letícia |
|17/06/2018|2.0|Adiciona Contextualização| Letícia |

# Sobre a ferramenta:

Esta página, à principio, mantém a documentação existente para a ferramenta que
propõe a realização de um Trace de Features *[BDDs](https://www.devmedia.com.br/desenvolvimento-orientado-por-comportamento-bdd/21127)*. Os artefatos aqui registrados
foram propostos para a disciplina de Arquitetura e Desenho da Universidade de
Brasília.

# BDD
No contexto desse projeto, é importante destacar o que é BDD para entender melhor o objetivo da ferramenta. BDD (Beahviour Driven Development) é técnica para desenvolvimento ágil que serve para criar testes e integrar regras de negócios com a tecnologia usada levando em conta o comportamento do software.

O foco em BDD é a linguagem e as interações usadas no processo do desenvolvimento. Os testes são escritos em língua nativa utilizando palavras-chave padrão para descrevê-los. Assim, é possível assegurar que cada unidade desenvolvida esteja de acordo com a sua especificação funcional.

No BDD tempos atributos que chamamos de features, onde se deve realizar uma descrição sobre a funcionalidade e os cenários, onde são descritos cenários de testes. *[Leia mais](https://www.devmedia.com.br/desenvolvimento-orientado-por-comportamento-bdd/21127)*


## Contextualização

A ideia principal da ferramenta é identificar, dentro de um projeto, quais são os
métodos mais analisados dado um conjunto de cenários BDD.

Isso se dá à partir do momento em que obtemos a lista de métodos executados para
cada: feature, cenário e todo o conjunto de features. Obter esses dados facilita
a rastreabilidade Requisito/Código.


![Processo](img/processo.png)
