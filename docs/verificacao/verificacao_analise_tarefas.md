# <center> Verificação da Análise de Tarefas

### Introdução
  A verificação é uma tentativa de assegurar que o produto seja construído corretamente, no sentido de que os produtos de saída de uma atividade atendem às
  especificações impostas a eles em atividades anteriores (SWEBOK® Guide V3.0, página 179). Tal atividade interessa apenas à equipe de desenvolvimento, 
  não sendo necessária o envolvimento do cliente (Milene Serrano e Maurício Serrano, aula 23). Contudo, o software não é o único alvo do processo de verificação,
  ou seja, esta atividade pode ser aplicada em manuais, modelos e outros artefatos (Gerência e Qualidade de Software - Aula 05 - Verificação e Validação - UNIVESP).
  Sendo assim, é nesse contexto que o documento atual consiste na aplicação de uma verificação, a fim de encontrar problemas e omissões frente ao que foi especificado 
  às atividades envolvidas no artefato Análise de Tarefas, evitando com que a herança de eventuais problemas acabe desencadeando em outros, assim reduzindo o custo de testes futuros.

### Metodologia
  Com o intuito de satisfazer o objetivo evidenciado na introdução, foi utilizado uma técnica de verificação denominada inspeção, uma técnica formal de revisão (Fagan, 1976). Essa técnica, cujas etapas estão evidenciadas **na imagem 1**, trata-se de um método gerencial de reuniões cujo objetido consiste em encontrar defeitos em documentos (Milene Serrano e Maurício Serrano, aula 23). Para isso, é necessário a realização de uma preparação prévia dos integrantes envolvidos nessa atividade, a fim de que os mesmos participem do processo com maior maestria. Além disso, vale ressaltar que tal tecnica é do tipo estática, isto é, o artefato poderá ser verificado sem a necessidade de execução de algum produto de software. Concomitante a isso, alguns tópicos, tais como checklists e classificação de defeitos, se fazem necessário para cumprir a proposta do método em questão. O primeiro refere-se à uma lista cujo domínio do conteúdo evidencia os defeitos mais comuns e tradicionais os quais foram analisados. Já o segundo, refere-se à classificação do defeito conforme algum critério. No contexto deste documento, o critério utilizado foi o grau de relevância. Os próximos tópicos abordarão cada etapa dessa metodologia com mais detalhe.

![image](https://user-images.githubusercontent.com/72039007/185969942-797112ed-9d58-461f-b3a2-97c4dbb1eec4.png)
  
 Imagem 1: Requisitos - Aula sobre Análise - Lucas e Pedro
    
Após o entendimento sobre as nuâncias da metodologia utilizada para elaboração do presente artefato, dois símbolos foram escolhidos para auxiliarem a elaboração dos checklists. A tabela 1 a seguir explica tal fato com mais detalhe.

Símbolo | Significado
--------|------------
✔ | Sim
✖ | Não
   
Tabela 1: Símbologia utilizada no checklist
  
# Checklist
Como dito anteriormente, checklist consiste em uma lista de quais defeitos mais comuns foram analisados, servindo de base para encontrar os defeitos tradicionais. Sendo assim, uma tabela foi elaboada com o intuito realizar essa etapa, sendo evidenciado um conjunto de perguntas específicas as quais foram verificadas se o artefato a satisfaz ou não. A tabela 2 a seguir contem o checklist usado nessa atividade.

Número | Questão                     | HTA01 | HTA02 |  GOMS  | Goal 0 | Goal 1 | Goal 2 | Goal 3 |
-------|-----------------------------|-------|-------|--------|--------|--------|--------|--------|
1  | A ortografia está correta ? |   ✔   |   ✔   | ✖      | ✔      |   ✔    |  ✔     |   ✔    |
2  | Existe uma breve introdução sobre o tópico a ser abordado? |   ✔   |   ✔   | ✔      | ✔      |   ✔    |  ✔     |   ✔    |
3  | A linguagem está simples e compreensível? |   ✔   |   ✔   |   ✔     | ✔      |   ✔    |  ✔     |   ✔    |
4  | As informações estão consistentes e objetivas? |   ✔   |   ✔   | ✔      | ✔      |   ✔    |  ✔     |   ✔    |
5  | As informações necessárias estão presentes? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
6  | A página possui referências do conteúdo? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
7  | As imagens possuem legendas? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
8  | A imagem pode ser expandida? |   ✖   |   ✖   |   ✖    | ✖      |   ✖    |  ✖     |   ✖    |
9  | Cada tarefa possui um diagrama? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
10  | Cada diagrama possui uma tabela de especificação? |   ✖   |   ✖   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
Taxa de acerto | 85,7%

<p align="center">Tabela 2: Checklist usado no processo de verificação do artefato Análise de tarefas</p>


# Classificação (parei a revisão aqui - Gustavo)

Número | Questão                     | HTA01 | HTA02 |  GOMS  | Goal 0 | Goal 1 | Goal 2 | Goal 3 |
-------|-----------------------------|-------|-------|--------|--------|--------|--------|--------|
1  | Os objetivos estão corretos? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
2  | As operações estão corretas? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
3  | O nível dos objetivos estã corretos? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
4  | Os níveis dos subobjetivos estã corretos? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
5  | As relações entre os subobjetivos estão corretos? |   ✔   |   ✔   |   ✔    | ✔      |   ✔    |  ✔     |   ✔    |
Taxa de acerto | 100%
   
   
<figcaption>Tabela 2: Checklist para Resultados específicos Análise de Tarefas </figcaption>


# Erros 

Em Regras de seleção, a palavra "representam" está escrita de maneira errada. Nenhuma imagem pode ser expandida.

# Conclusão
Com a elaboração deste documento, o repertório de conhecimento sobre o artefato verificado aumentou para todos os envolvidos na sua elaboração. Isso se deve ao exercício mental envolvido nas tarefas de preparação e investigação de eventuais erros, pois isso demanda o conhecimento dos fatores considerados corretos na metodologia em si. Somado a isso, partindo do pressuposto de que tal tecnica permite a identificação prévia de erros, podendo auxiliar o projeto como um todo, pois minimiza atividades futuras de testes, reduzindo o custo total da operação.


# Referências bibliográficas
   
> [1] - Requisitos - Aula 23. Disponível em: <a href='https://aprender3.unb.br/pluginfile.php/993660/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf'> https://aprender3.unb.br/pluginfile.php/993660/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf</a><br>
> [2] - SWEBOK® Guide V3.0 - página 179. Disponível em: <a href='https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3'> https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3</a><br>
> [3] - Gerência e Qualidade de Software, Verificação e Validação (UNIVESP) - Aula 05. Disponível em: <a href='https://youtu.be/1Y-1zz6rZxo?t=22'> https://youtu.be/1Y-1zz6rZxo?t=22</a><br>
> [4] - Artefato - Backlog. Disponível em: <a href='https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/modelagemRequisitos/backlog'> https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/modelagemRequisitos/backlog</a>
> [5] - Aula - Análise.  Disponível em: <a href='https://aprender3.unb.br/pluginfile.php/2124539/mod_resource/content/2/Aula%20An%C3%A1lise%20.pdf'>https://aprender3.unb.br/pluginfile.php/2124539/mod_resource/content/2/Aula%20An%C3%A1lise%20.pdf</a><br>

# Histórico de versões
|Versão|Data|Autor|Revisor|
|------|----|-----|-------|
|1.0|14/8/2022|Luan Vasco| Gustavo Martins |
|2.0|22/8/2022|Gustavo Martins| Luan Vasco |
