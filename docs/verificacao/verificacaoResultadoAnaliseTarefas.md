# <center> Verificação - Relato da Avaliação da Análise de Tarefas

### Introdução
  A verificação é uma tentativa de assegurar que o produto seja construído corretamente, no sentido de que os produtos de saída de uma atividade atendem às
  especificações impostas a eles em atividades anteriores (SWEBOK® Guide V3.0, página 179). Tal atividade interessa apenas à equipe de desenvolvimento, 
  não sendo necessária o envolvimento do cliente (Milene Serrano e Maurício Serrano, aula 23). Contudo, o software não é o único alvo do processo de verificação,
  ou seja, esta atividade pode ser aplicada em manuais, modelos e outros artefatos (Gerência e Qualidade de Software - Aula 05 - Verificação e Validação - UNIVESP).
  Sendo assim, é nesse contexto que o documento atual consiste na aplicação de uma verificação, a fim de encontrar problemas e omissões frente ao que foi especificado 
  às atividades envolvidas no artefato [Relato de Avaliação da Análise de tarefas](https://interacao-humano-computador.github.io/2022.1-Dominio-Publico/#/design/Fase1/relatoAvaliacao), evitando com que a herança de eventuais problemas acabe desencadeando em outros, assim reduzindo o custo de testes futuros.

### Metodologia
  Com o intuito de satisfazer o objetivo evidenciado na introdução, foi utilizado uma técnica de verificação denominada inspeção, uma técnica formal de revisão (Fagan, 1976). Essa técnica, cujas etapas estão evidenciadas **na imagem 1**, trata-se de um método gerencial de reuniões cujo objetido consiste em encontrar defeitos em documentos (Milene Serrano e Maurício Serrano, aula 23). Para isso, é necessário a realização de uma preparação prévia dos integrantes envolvidos nessa atividade, a fim de que os mesmos participem do processo com maior maestria. Além disso, vale ressaltar que tal tecnica é do tipo estática, isto é, o artefato poderá ser verificado sem a necessidade de execução de algum produto de software. Concomitante a isso, alguns tópicos, tais como checklists e classificação de defeitos, se fazem necessário para cumprir a proposta do método em questão. O primeiro refere-se à uma lista cujo domínio do conteúdo evidencia os defeitos mais comuns e tradicionais os quais foram analisados. Já o segundo, refere-se à classificação do defeito conforme algum critério. No contexto deste documento, o critério utilizado foi o grau de relevância. Os próximos tópicos abordarão cada etapa dessa metodologia com mais detalhe.


<img align = " center"> ![image](https://user-images.githubusercontent.com/72039007/185969942-797112ed-9d58-461f-b3a2-97c4dbb1eec4.png) </img>
  
 Imagem 1: Requisitos - Aula sobre Análise - Lucas e Pedro
 
Após o entendimento sobre as nuâncias da metodologia utilizada na elaboração do presente artefato, dois símbolos foram escolhidos para auxiliarem a elaboração dos checklists. A tabela 1 a seguir explica tal fato com mais detalhe.

Símbolo | Significado
--------|------------
✔ | Sim
✖ | Não
-- | Não se aplica

<p>Tabela 1: Símbologia utilizada no checklist</p>
  
# Checklist
Como dito anteriormente, checklist consiste em uma lista de quais defeitos mais comuns foram analisados, servindo de base para encontrar os defeitos tradicionais. Sendo assim, a **tabela 2** a seguir foi elaboada com o intuito realizar essa etapa, sendo evidenciado um conjunto de perguntas específicas as quais foram verificadas se o artefato a satisfaz ou não. A tabela 2 a seguir contem o checklist usado nessa atividade.

Número | Questão                     | Resposta | Comentários |
-------|-----------------------------|-------|-----------------------------|
1  | Os erros de portugues (sintaxe, semântica e gramática) foram minimizados ? |   ✖   | 
2  | Existe uma breve introdução sobre o tópico a ser abordado? |   ✔   |
3  | A linguagem está simples e compreensível? |   ✔   |
4  | As informações estão consistentes e objetivas? |   ✔   |
5  | O artefato possui uma conclusão? |   ✔   |
6  | A página possui referências do conteúdo? |   ✔   |
7  | As imagens e tabelas possuem legendas? |   ✔   |
8  | As imagens e tabelas estão sendo invocadas no texto? |   ✔   |
9  | O artefato apresenta e explica a metodologia utilizada? |   ✖   | Faltou explicar oque seria uma AHT, falou apenas o objetivo
10  | O artefato aplica corretamente a metodologia escolhida? |   ✖   |
11  | O artefato possui um revisor? |   ✔   |
12  | O artefato utiliza hiperlinks? |   ✔   | 
13  | Os hiperlinks estão redirecionando corretamente? |   ✔   |
14  | O artefato possui um histórico de versão padronizado conforme o projeto? |   ✔   |
15  | O artefato contem a avaliação e a interpretação dos dados conforme planejado pelo item E do framework DECIDE? |   ✔   |
16  | É possivel verificar se o entrevistador solicitou o preenchimento do termo de consentimento ao entrevistado, conforme planejado? | ✖
17  | O entrevistador realizou as perguntas do roteiro conforme planejado? | ✔
18  | Os objetivos da avaliação foram alcançados? | ✔
19  | Os participantes voluntários se enquadram no perfil estipulado? | ✔
20  | A entrevista ocorreu em um ambiente adequado (conforme o planejamento)? | ✔
Taxa de acerto | 80% 

<p align = "center">Tabela 2: tabela ao final da etapa atual - Checklist</p>


# Classificação
Além da elaboração do checklist, a metodologia impõe uma classificação dos defeitos encontrados. A tabela 2, evidenciada a baixo, consiste em uma evolução da tabela 1, pois possui o acréscimo de uma nova coluna relativa à relevância. Associado a isso, a fim de esclarecer oque seria tal relevância, deve-se entende-la como o nível de impacto negativo que tal problema traz ao artefato. Concomitante a isso, a decisão de replicar a tabela anterior com o acrescimo de uma nova coluna se deve ao fato de, segundo a sistemática da técnica de inspeção, a classificação ser realizada após o término da etapa referente ao checklist.

Número | Questão                     | Resposta | Comentários | Relevância | 
-------|-----------------------------|-------|-----------------------------| ----------- |
1  | Os erros de portugues (sintaxe, semântica e gramática) foram minimizados ? |   ✖   || Baixo |
2  | Existe uma breve introdução sobre o tópico a ser abordado? |   ✔   || Alto |
3  | A linguagem está simples e compreensível? |   ✔   || Médio |
4  | As informações estão consistentes e objetivas? |   ✔   || Alto |
5  | O artefato possui uma conclusão? |   ✔   || Alto |
6  | A página possui referências do conteúdo? |   ✔   || Alto |
7  | As imagens e tabelas possuem legendas? |   ✔   || Médio |
8  | As imagens e tabelas estão sendo invocadas no texto? |   ✔   || Baixo |
9  | O artefato apresenta e explica a metodologia utilizada? |   ✖   | Faltou explicar oque seria uma AHT, falou apenas o objetivo | Alto
10  | O artefato aplica corretamente a metodologia escolhida? |   ✔   || Alto |
11  | O artefato possui um revisor? |   ✔   || Alto |
12  | O artefato utiliza hiperlinks? |   ✔   || Baixo |
13  | Os hiperlinks estão redirecionando corretamente? |   ✔   || Alto |
14  | O artefato possui um histórico de versão padronizado conforme o projeto? |   ✔   || Médio |
15  | O artefato contem a avaliação e a interpretação dos dados conforme planejado pelo item E do framework DECIDE? |   ✔   || Alto |
16  | É possivel verificar se o entrevistador solicitou o preenchimento do termo de consentimento ao entrevistado, conforme planejado? | ✖ || Alto |
17  | O entrevistador realizou as perguntas do roteiro conforme planejado? | ✔ || Alto |
18  | Os objetivos da avaliação foram alcançados? | ✔ || Alto |
19  | Os participantes voluntários se enquadram no perfil estipulado? | ✔ || Alto |
20  | A entrevista ocorreu em um ambiente adequado (conforme o planejamento)? | ✔ || Médio |
Taxa de acerto | 80% 

<p align ="center">Tabela 2: Checklist atualizado com a coluna "Relevância", satisfazendo a etapa de classificação </p>

# Conclusão
Com a elaboração deste documento, o repertório de conhecimento sobre o artefato verificado aumentou para todos os envolvidos na sua elaboração. Isso se deve ao exercício mental envolvido nas tarefas de preparação e investigação de eventuais erros, pois isso demanda o conhecimento dos fatores considerados corretos na metodologia em si. Somado a isso, partindo do pressuposto de que tal tecnica permite a identificação prévia de erros, é visível que sua aplicação auxilia o projeto como um todo, minimiza atividades futuras de testes devido a correção prévia de erros, reduzindo o custo total da operação.

# Referências bibliográficas
   
> [1] - Requisitos - Aula 23. Disponível em: <a href='https://aprender3.unb.br/pluginfile.php/993660/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf'> https://aprender3.unb.br/pluginfile.php/993660/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf</a><br>
> [2] - SWEBOK® Guide V3.0 - página 179. Disponível em: <a href='https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3'> https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3</a><br>
> [3] - Gerência e Qualidade de Software, Verificação e Validação (UNIVESP) - Aula 05. Disponível em: <a href='https://youtu.be/1Y-1zz6rZxo?t=22'> https://youtu.be/1Y-1zz6rZxo?t=22</a><br>
> [4] - Artefato - Backlog. Disponível em: <a href='https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/modelagemRequisitos/backlog'> https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/modelagemRequisitos/backlog</a>
> [5] - Aula - Análise.  Disponível em: <a href='https://aprender3.unb.br/pluginfile.php/2124539/mod_resource/content/2/Aula%20An%C3%A1lise%20.pdf'>https://aprender3.unb.br/pluginfile.php/2124539/mod_resource/content/2/Aula%20An%C3%A1lise%20.pdf</a><br>

# Histórico de versões
|Versão|Data|Autor|Revisor|
|------|----|-----|-------|
|1.0|22/8/2022| Gustavo Martins| Luan Vasco |
