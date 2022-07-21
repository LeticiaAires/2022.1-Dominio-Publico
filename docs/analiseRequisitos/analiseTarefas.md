# Análise de tarefas

## Introdução

A análise de tarefas tem por objetivo, compreender sobre o trabalho dos usuários, como realizam esse trabalho e por quê realizam. Ela pode ser utilizada em diferentes momentos no desenvolvimento de um software: para a análise da situação atual (apoiada ou não por um sistema computacional), para o (re)design de um sistema computacional ou para a avaliação do resultado de uma intervenção que inclua a introdução de um (novo) sistema computacional.

As análises de tarefas devem envolver um processo de coleta de dados responsáveis por definir objetivos dos usuários dentro da plataforma. No livro Interação Humano-Computador de Simone Diniz e Bruno Siqueira, é apresentado três dos métodos mais comuns de análise de tarefas: O Análise Hierárquica de Tarefas (com a sigla em inglês HTA), GOMS e o ConcurTaskTrees.

No presente projeto, utilizaremos o **HTA** e o **GOMS**.

## Análise Hierárquica de Tarefas (HTA)

Esta técnica ajuda a relacionar o que as pessoas fazem (ou se recomenda que façam), por que o fazem, e quais as consequências caso não o façam corretamente. Ela se baseia em psicologia funcional, e não comportamental, como eram as abordagens da época em que foi criada.

## Motivação

Essa técnica foi escolhida devido à facilidade de visualização e entendimento das operações e objetivos descritos nela. Isso se concretiza pois, se comparada a outras técnicas, como o GOMS, essa técnica se baseia na representação visual e hierárquica e na fácil leitura de elementos.
## Metodologia

Segue, na _figura 1_ e nos dois próximos pontos, uma legenda para os elementos que foram utilizados nas HTA criadas neste método.

<div align="center">
<img src="assets/imagens/analise-tarefas-legenda.svg" alt="Legenda">
    <p><i>Figura 1 - Legenda para as HTAs</i></p>
</div>

- **Objetivo:** Um objetivo é um estado específico de coisas, um estado final. Podendo ser definido por um ou mais eventos ou por valores fisicamente observáveis de uma ou mais variáveis, que atuam como critério de alcance do objetivo , em última instância, do desempenho do sistema.
- **Operação:** Uma operação é especificada pelas circunstâncias nas quais o objetivo é ativado (input ou entrada), pelas atividades ou ações (actions) que contribuem para atingí-lo e pelas condições que indicam o seu atingimento (feedback).

Seguindo o método em questão, foram confeccionados diagramas para as principais tarefas encontradas, sendo elas separadas nos itens **HTA01** (_figura 2_) e **HTA02** (_figura 3_).

### HTA01 - Buscar Obras

<div align="center">
<img src="assets/imagens/analise-tarefas-busca.svg" alt="Buscar Obras">
    <p><i>Figura 2 - HTA para busca de obras</i></p>
</div>

### HTA02 - Acessar sites relacionados

<div align="center">
<img src="assets/imagens/analise-tarefas-acesso.svg" alt="Acesso a Sites" width="400px">
 <p><i>Figura 3 - HTA para sites relacionados</i></p>
</div>


## GOMS
O GOMS é um método de análise de tarefas proposto por Card et al. (1983) e propõe um conjunto de modelos (Objetivos, Operadores, Métodos e Regras de Seleção) e tem como objetivo analisar o desempenho de usuários competentes de sistemas computacionais. Os modelos GOMS são úteis para prever o desempenho pelo impacto das decisões de design. Se aplica principalmente quando os usuários realizam tarefas que já dominam.
## Motivação
A escolha desse método foi devido ao projeto ser desenvolvido a partir de um sistema já existente, sendo assim, pressupõe-se que os usuários realizem tarefas que já dominem e o objetivo é apenas fornecer uma representação formalizada que pode ser utilizada para prever o desempenho e propor melhorias ao sistema.

## Metodologia
Esse método descreve uma tarefa e o conhecimento do usuário sobre como realizá-la, levando em conta os objetivos, operadores, métodos e regras de seleção. 
- Objetivos: Representam o motivo, o que usuário quer realizar ao utilizar o software;
- Operadores: São primitivas internas ou externas;
- Os métodos são sequências de subobjetivos e operadores que permitem que um objetivo principal e maior seja atingido;
- Regras de seleção: Represnetam tomadas de decisão que os usuários realizam sobre qual método utilizar em determinada situação.

## Resultados 

GOAL 0: Encontrar a obra desejada 

    GOAL 1:  Pesquisar obra
        METHOD 1.A: Utilizar a pesquisa básica do site
        (SEL.RULE: O usuário deseja procurar uma obra por várias informações ou apenas por tipo de obra)
            OP. 1.A.A.1.: Deslocar o mouse até "Pesquisa Básica" no canto superior esquerdo;
            OP. 1.A.A.2.: Clicar no campo que deseja preencher para buscar obra. (O campo Tipo de Mídia é o único obrigatório;
            OP. 1.A.A.3: Selecionar nos campos de seleção e escrever nos de texto;
            OP. 1.A.A.4: Deslocar o mouse para o botão "pesquisar";
            OP. 1.A.A.5: Clicar com o botão esquerdo do mouse;

        METHOD 1.B: Utilizar a pesquisa por conteúdo
        (SEL.RULE: O usuário deseja procurar uma obra presente no acervo por uma palavra chave)
            OP. 1.A.B.1.: Deslocar o mouse até "Pesquisa por Conteúdo" no canto inferior esquerdo da tela principal;
            OP. 1.A.B.2.: Preencher com a palavre chave;
            OP. 1.A.B.4: Deslocar o mouse para o botão "pesquisar";
            OP. 1.A.B.5: Clicar com o botão esquerdo do mouse;
        
        METHOD 1.C: Utilizar a pesquisa por teses e dissertações
        (SEL.RULE: O usuário deseja procurar uma obra presente no acervo de Teses e Dissertações com uma palavra chave)
            OP. 1.A.C.1.: Deslocar o mouse até "Pesquisa Teses e Dissertações" no canto inferior esquerdo;
            OP. 1.A.C.2.: Preencher com a palavre chave;
            OP. 1.A.C.3: Deslocar o mouse para o botão "pesquisar";
            OP. 1.A.C.4: Clicar com o botão esquerdo do mouse;

        METHOD 1.D: Utilizar a pesquisa por nome do autor
        (SEL.RULE: O usuário deseja procurar uma obra presente no acervo pela inicial do autor)
            OP. 1.A.D.1.: Deslocar o mouse até as letras disponíveis;
            OP. 1.A.D.2.: Selecionar a letra da inicial do autor;

    GOAL 2: Selecionar a obra dentre as resultantes:
        METHOD 2.A: Utilizar a rolagem do mouse
        (SEL.RULE: A obra que o usuário deseja encontrar não está visível nos primeiros resultados e esse precisa encontrá-la)
            OP. 2.A.A.1.: Deslizar o mouse para a tabela de obras resultantes;
            OP. 2.A.A.2.: Utilizar a rolagem do mouse para ir procurando a obra na tabela;
            OP. 2.A.A.3.: Deslizar o mouse para o nome da obra;
            OP. 2.A.A.4.: Selecionar o link com o botão esquerdo do mouse;

        METHOD 2.B: Utilizar a pesquisa para filtrar mais os resultados.
        (SEL.RULE: A obra que o usuário deseja encontrar não está visível nos primeiros resultados e esse precisa encontrá-la)
            OP. 2.A.B.1.: Deslizar o mouse para a pesquisa na parte superior da tela;
            OP. 2.A.B.2.: Completar mais campos a fim de filtrar melhor os resultados;
            OP. 2.A.B.3.: Se a obra estiver no acervo, deslizar o mouse até a tabela com a obra;
            OP. 2.A.B.4.: Selecionar o link com o botão esquerdo do mouse;

    GOAL 3: Baixar a obra
        OP. 2.A.A.1.: Ver os detalhes da obra;
        OP. 2.A.A.2.: Deslizar o cursos até o botão "Baixar";
        OP. 2.A.A.3.: Selecionar o botão;



### Referências Bibliográficas

> - Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação
Humano-Computador e Experiência do usuário. Autopublicação.

## Histórico de versão

| Versão | Data       | Descrição                                 | Autor        | Revisor   |
| ------ | ---------- | ----------------------------------------- | ------------ | --------- |
| 0.1    | 17/07/2022 | Documento inicial                         | Gabriel Moretti    | Adne Moretti |
| 0.2    | 19/07/2022 | Adicionando análise de tarefas por GOMS   | Adne Moretti | Gabriel Moretti 
