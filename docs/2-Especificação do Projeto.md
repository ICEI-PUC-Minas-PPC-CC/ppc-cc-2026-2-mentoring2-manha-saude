
# ESPECIFICAÇÃO DO PROJETO

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>


## Personas

| **Clemilton Fernandes** - Persona 1|  |  |
|:-----------------------:|---|---|
| <img width="200" height="200" alt="IMAGEM PERSONAGEM  1" src="https://github.com/user-attachments/assets/bdf56705-5844-4669-b15f-81b942c84e7b" />| **Idade:** 46 anos.<br><br>**Naturalidade:** Poços de Caldas - Minas Gerais.<br><br>**Ocupação:** Professor | **Atribuições:** Ministrar aulas para alunos do ensino médio no período integral e noturno em uma escola pública. |
| **Motivações:** Deseja conferir de forma rápida sobre seus níveis e melhorias em seu tratamento da diabetes. | **Frustrações:** Dificuldade para gerenciar a vida profissional e pessoal, pois trabalha durante um longo período e possui intervalos curtos e pouco flexíveis. | **Hobbies e história:** Almeja conseguir atendimentos rápidos e que não atrapalhem seu trabalho, evitando grandes deslocamentos. |



| **Samuel Silva** - Persona 2 |  |  |
|:----------------:|---|---|
<img width="1024" height="1024" alt="firmimno" src="https://github.com/user-attachments/assets/c09461fa-c547-4d0f-9b78-54c35219d39e" /> | **Idade:** 43 anos.<br><br>**Naturalidade:** Pirassununga - São Paulo.<br><br>**Ocupação:** Gari. | **Atribuições:** Realiza a coleta de resíduos nas lixeiras e vias públicas, recolhendo os sacos de lixo e depositando-os no caminhão de coleta. |
| **Motivações:** Precisa acompanhar e levar o pai às unidades de saúde para realizar consultas e acompanhamento médico, devido ao alto risco de desenvolver trombose. | **Frustrações:** Dificuldade para gerenciar a vida profissional e pessoal, pois, além de enfrentar jornadas de trabalho exaustivas, precisa cuidar do pai em casa, que se recuperou de um câncer e atualmente apresenta alto risco de desenvolver trombose. | **Hobbies, história:** Almeja conseguir conciliar sua rotina de trabalho com os cuidados do pai, pois atualmente se sente sobrecarregado com as responsabilidades e busca formas de otimizar seu tempo e facilitar sua rotina. |


| **Maria Aparecida** - Persona 3 |  |  |
|:-------------------:|---|---|
<img width="200" height="200" alt="maria" src="https://github.com/user-attachments/assets/c045f2d1-30d7-481d-9201-69cd6f4b8793" /> |  **Idade:** 67 anos.<br><br>**Naturalidade:** Poços de Caldas - Minas Gerais.<br><br>**Ocupação:** Sem ocupação remunerada, não possui renda própria e depende de auxílios financeiros. | **Atribuições:** Administrar sua rotina e suas necessidades pessoais, buscando acesso aos serviços de saúde disponíveis para realizar o tratamento de que necessita. |
| **Motivações:** Deseja conseguir atendimento e acompanhamento para seus problemas de ansiedade e depressão, buscando melhorar sua saúde mental e sua qualidade de vida. | **Frustrações:** Não possui condições financeiras nem meios de locomoção para chegar aos locais onde estão sendo oferecidos os atendimentos pela faculdade, dificultando seu acesso ao tratamento. | **Hobbies, história:** Viúva, não possui filhos e vive sozinha. Por depender de auxílios financeiros e não possuir meios próprios de transporte, encontra dificuldades para se deslocar e ter acesso aos atendimentos de saúde de que necessita. |


## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA`            | QUERO/PRECISO ... `FUNCIONALIDADE`                             | PARA ... `MOTIVO/VALOR`                                              |
| ------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------- |
| Clemilton Fernandes - Persona 1 | Ter acesso rápido às informações sobre meus níveis de diabetes | Acompanhar minha condição de saúde e as melhorias no meu tratamento. |

| EU COMO... `PERSONA`     | QUERO/PRECISO ... `FUNCIONALIDADE`                       | PARA ... `MOTIVO/VALOR`                                                                        |
| ------------------------ | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Samuel Silva - Persona 2 | Agendar e acompanhar os atendimentos de saúde do meu pai | Facilitar o acompanhamento médico e organizar minha rotina de trabalho e cuidados com meu pai. |

| EU COMO... `PERSONA`        | QUERO/PRECISO ... `FUNCIONALIDADE`                               | PARA ... `MOTIVO/VALOR`                                                            |
| --------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Maria Aparecida - Persona 3 | Ter acesso aos atendimentos de saúde próximos à minha residência | Facilitar meu acesso ao tratamento mesmo sem possuir meios próprios de transporte. |


## Requisitos Funcionais

### Persona 1

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RF-001 | O sistema deverá permitir que o usuário consulte informações relacionadas ao acompanhamento e à evolução do tratamento da diabetes | ALTA |
| RF-002 | O sistema deverá permitir que o usuário consulte seus atendimentos e informações de saúde de forma remota, reduzindo a necessidade de deslocamento até a unidade de saúde | ALTA |


### Persona 2

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RF-003 | O sistema deverá permitir que o usuário acompanhe informações de saúde de um familiar sob seus cuidados | ALTA |
| RF-004 | O sistema deverá permitir que o usuário consulte informações sobre consultas, atendimentos e acompanhamento médico do familiar | ALTA |


### Persona 3

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RF-005 | O sistema deverá permitir que o usuário consulte informações sobre atendimentos e acompanhamento relacionados à saúde mental | ALTA |
| RF-006 | O sistema deverá permitir que o usuário solicite ou acompanhe atendimentos de saúde de forma remota, diminuindo a necessidade de deslocamento | ALTA |



## Requisitos Não Funcionais

### Persona 1

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RNF-001 | O sistema deve apresentar as informações solicitadas pelo usuário de forma rápida, com tempo de resposta de no máximo 3 segundos | ALTA |
| RNF-002 | O sistema deve ser responsivo, permitindo sua utilização adequada em computadores, tablets e celulares | ALTA |


### Persona 2

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RNF-003 | O sistema deve possuir uma interface simples e organizada, permitindo que as informações de saúde do familiar sejam localizadas com facilidade | ALTA |
| RNF-004 | O sistema deve garantir a segurança e a privacidade das informações de saúde armazenadas e acessadas pelo usuário | ALTA |


### Persona 3

| ID | Descrição do Requisito | Prioridade |
|----|-------------------------|------------|
| RNF-005 | O sistema deve possuir uma interface simples e intuitiva, facilitando sua utilização por usuários idosos ou com pouca familiaridade com recursos digitais | ALTA |
| RNF-006 | O sistema deve funcionar adequadamente em dispositivos móveis e possuir uma interface adaptável a diferentes tamanhos de tela | MÉDIA |
### Artefatos para levantamento de dados

Nesta seção, caso seu grupo vá realizar algum tipo de levantamento de dados/entrevistas, descreva o(s) artefato(s) produzidos para tal. Também deverá ser descrita qual estratégia será utilizada para este levantamento. Por exemplo: como os questionários serão aplicados? (_in loco_, via disponibilização pela _web_ etc), qual material/estratégia de divulgação será utilizado? 

Não se preocupe em descrever os resultados agora, eles deverão ser descritos apenas na seção "Detalhamento preliminar" (Etapa 03).
