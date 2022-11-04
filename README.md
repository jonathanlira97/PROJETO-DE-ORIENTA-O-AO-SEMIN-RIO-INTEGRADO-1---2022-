#CRIAÇÃO DO DIAGRMA DE GANNT - DISCIPLINA DE PROJETO INTEGRADOR I!

**Mermaid permite criar e visualizar diagramas.**

Este exemplo é um modelo de cronograma simples, documentação sobre o gráfico de está [disponível aqui](https://github.com/mermaid-js/mermaid/blob/develop/docs/gantt.md).

```mermaid
    gantt
    title Cronograma de atividades do projeto
    dateFormat  YYYY-MM-DD
    section Pesquisa
    Desenvolvimento com as tecnologias     :   a1, 2022-11-08, 21d
    Uso dos recursos    : a2, 2022-11-15, 28d
    Ferramentas   : a3, after a2, 16d
    section Documentação
    Pré-projeto     :a1, 2022-11-01, 15d
    Levantamento de literatura   :a2,after a1  , 20d
    Construção da documentação final  :a3, 2022-12-27, 21d
    section Desenvolvimento
    Criação do protótipo de telas   : c2, 2022-11-22, 15d
    section Prototipação
    Criação de telas do sistema     :       c2,     after a1  , 12d
    Criação do protótipo      :c3,     after c2, 14d
    section Defesa
    Preparação dos slides :p1, after c3, 10d
    Ensaio da apresentação :p2, after c3, 7d
    Apresentação e entrega  :milestone, after p1, 1d
