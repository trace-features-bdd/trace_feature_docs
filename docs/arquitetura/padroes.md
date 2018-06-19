# Padrões

## Estilo Arquitetural
O projeto atualmente, dentro escopo da disciplina, pode ser identificado com o estilo Stand-alone: a ferramenta roda apenas na máquina do usuário e não depende de terceiros para funcionar.

Apesar disso, é interessante observar que a perspectiva é de que o projeto seja um sistema distribuído dentro do que se espera na aplicação como um todo. A ferramenta deverá continuar rodando na máquina do usuário, e, a partir daí, o arquivo json será enviado para o servidor da aplicação completa. Isso evita que o servidor precise realizar o trabalho de executar os sistemas que serão analisados, deixando a cargo da máquina do usuário interessado e, com o resultado enviado para o servidor, o usuário poderá continuar o seu trabalho pela web.

## Padrões de Projeto
### Composite
O Composite é implementado na parte de Cenários. Cada cenário pode descrever apenas um procedimento ou é possível também que vários cenários simples estejam contidos dentro de outro cenário.

### Strategy
Considerando que se deseja que a ferramenta funcione para várias linguagens, o Strategy é aplicado para que o software se comporte de maneira diferente de acordo com a linguagem a ser analisada.

### Facade
O Facade é usado para executar uma série de procedimentos na iniciação do software, tais como identificar a linguagem do projeto a ser analisado e executar o setup. 
