#CRIAÇÃO DO DIAGRMA DE GANNT - DISCIPLINA DE PROJETO INTEGRADOR I - "Projeto de Desenvolvimento de Software no Aux. de Deficientes visuais"!

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
    Criação do Diagrama de Componentes: c3, 2022-12-06, 15d
    section Desenvolvimento
    Criação do protótipo de telas  :  c2, after a2, 14d
    Aplicativo final   :     c3, after a3, 21d
    section Prototipação
    Criação de telas do sistema     :    c3, 2022-12-06, 21d
    Criação do protótipo      :c3,     after c2, 14d
    section Defesa
    Preparação dos slides :p1, after c3, 14d
    Ensaio da apresentação :p2, after c3, 18d
    Apresentação e entrega  :milestone, after p1, 1d
    
``` 
## O cronograma pode prever os seguintes tópicos sugeridos:
- Levantamento da literatura: quanto tempo você demora para ler e organizar as referências bibliográficas? 
- Escolha do instrumento e preparação para coleta de dados: quanto tempo será gasto para escolher os instrumentos que serão usados na pesquisa? (Questionários, entrevistas e escalas, por exemplo). 
- Levantamento de dados: quanto tempo é preciso para levantar os dados que serão usados no estudo? 
- Escrita da parte teórica: quanto tempo será gasto para escrever o relatório? 
- Análise dos dados: qual é o tempo necessário para organizar os dados coletados em planilhas e tabulá-los? 
- Discussão dos resultados: quanto tempo você vai gastar para articular os seus dados com os dados de outros autores que pesquisaram as mesmas variáveis? 
- Elaboração da conclusão e referências: quanto tempo é necessário para escrever as considerações finais e colocar a lista de referências bibliográficas nas normas da ABNT? 
- Ajustes finais: de quanto tempo você precisa para revisar a formatação? 
- Criação da apresentação: qual é o tempo necessário para elaborar os slides e ensaiar a apresentação? 
- Defesa: Quando o trabalho será apresentado para a banca? 


## DESCRIÇÃO E APRESENTAÇÃO DAS INTERFACES GRÁFICAS PARA O APLICATIVO (Jonathan)
    Esse trabalho consiste em apresentar capturas do protótipo das interfaces gráficas, e suas respectivas características para assim informar sobre as funcionalidades     e fluxos para o aplicativo que será desenvolvido e utilizado durante o desenvolvimento do Projeto Integrador como um todo.

    ###Interface 1: Tela Inicial (jonathan)
    Nesta tela, temos o início de toda a integração do serviço a ser disponibilizado. Com a logomarca que simboliza a característica da natureza do serviço prestado no     uso do transporte público intermunicipal. Nesta tela tem 2 opções: 1ª o de “Cadastrar usuário” pelo primeiro acesso, e 2ª opção – “Entrar” com seu cadastro pela       primeira vez, onde vai poder entrar diretamente com o uso dos dados usados para realizar seu cadastro como usuário que forma utilizados na opção anteriormente.

    ![Tela Inicial](tela inical de acesso ao sistema.png)
    
    
    ###Interface 2: Menu de Login (jonathan)
    Nesta tela, o suário é direcionado após passar pela primeira interface para inserir seus dados pessoais nos campos - Email e Senha já com o uswo do recurso (leitor     captador de voz do software)  para facilitar o manuseio por parte do usuário: "deficie3ntes visuais"
   
   
    ###Interface 3: Menu de Cadastro (jonathan)
    Na interface destinada ao menu cadastramento do usuário ele tem seu primeiro acesso, após a Tela Inicial. Aqui possui 3 campos de preenchimento de dados pessoais:     nome do usuário, Email, senha a ser criad, e em cada um desses campos com o receio (leitor captador de voz do software) para manter acessibilidade especial. Após       essa tela ele será destinado a tela Menu -4 com as opções de serviço.
    
    
    

    
    
    
   
