# Documento de Visão

## 1. Introdução
### 1. Propósito do documento de requisitos
Este documento visa a apresentação do sistema **LocationVan** produzido pela equipe **JuremasTEC Social**. Este documento contém todos os requisitos bem como seu escopo e demais informações relevantes para a implementação deste projeto.
### 2. Escopo do Produto
O Sistema **LocationVAN** foi criado para modificar a forma que as viagens são feitas e organizadas, criando possibilidade para organizar Excursões, Lotações e Viagens em geral, sendo assim, uma alternativa à complicação existente na atual organização destes tipos de viagens. O Sistema conta com possibilidades para passageiros, motoristas, empresas em geral. Criando possibilidade para dar "matches" e encontrar parceiros para ambas os lados.

## 2. Descrição Geral
   ### 1. Requisitos Funcionais
   
| Identificador  | RF001                                                                                                                         |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Cadastrar Usuario                                                                                                             |
| **Descrição**  | Requisito para a criação de usuarios, que eles criem o seu perfil e possam usufruir de todos os beneficios de ser um usuario. |
| **Prioridade** | Alta                                                                                                                          |
|                |                                                                                                                               |  |
---
| Identificador  | RF002                                                                                                                                         |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Cadastrar Motorista                                                                                                                           |
| **Descrição**  | Requisito para que o Usuário, criado anteriormente possa se cadastrar como Motorista para que ele possa criar vagas ou viagens no Aplicativo. |
| **Prioridade** | Alta                                                                                                                                          |
|                |                                                                                                                                               |  |
---
| Identificador  | RF003                                                                                                                     |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Cadastrar Viagem                                                                                                          |
| **Descrição**  | Requisito para que o Motorista, cadastrado anteriormente possa cadastrar uma viagem, para assim achar outros passageiros. |
| **Prioridade** | Alta                                                                                                                      |
|                |                                                                                                                           |  |
---
| Identificador  | RF004                                                                                                           |
| -------------- | --------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Cadastrar Viagem ( Passageiro )                                                                                 |
| **Descrição**  | Requisito para que o Usuário Passageiro, possa demandar uma vaga para uma viagem, seja ela excursão ou lotação. |
| **Prioridade** | Alta                                                                                                            |
|                |                                                                                                                 |  |
---
| Identificador  | RF005                                                                                                                                                                       |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Cadastrar Viagem ( Passageiro ) // Excursão                                                                                                                                 |
| **Descrição**  | Requisito para que o Usuário Passageiro ou um grupo, possa demandar vagas para uma  certa viagem, seja ela excursão ou lotação. Visando assim viajar esse grupo todo junto. |
| **Prioridade** | Alta                                                                                                                                                                        |
|                |                                                                                                                                                                             |  |
---
| Identificador  | RF006                                                                                  |
| -------------- | -------------------------------------------------------------------------------------- |
| **Nome**       | Desistir de Viagem                                                                     |
| **Descrição**  | Requisito para que o Usuário Passageiro ou mesmo o condutor, possa desistir da viagem. |
| **Prioridade** | Alta                                                                                   |
|                |                                                                                        |  |
   
   ### 2. Requisitos não-funcionais
| Identificador  | RNF001                                                                                                                         |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Nome**       | Acessibilidade                                                                                                            |
| **Descrição**  | Deve ser acessivel pelo o navegador. |
|                |                                                                                                                      

---
| Identificador  | RNF002                                                                                  |
| -------------- | -------------------------------------------------------------------------------------- |
| **Nome**       | Portabilidade                                                                     |
| **Descrição**  | O sistema deve roda em sistemas operacionais Linux, Windows, Android e IOS |
|                |                                                                                        |  |
   
   ### 3. Perfis dos usuários
   O sistema poderá ser utilizado por diversos usuários. Temos os seguintes perfis:
1. Perfil Administrador
	- Este perfil tem acesso a todos os dados, e pode alterar dependendo da nescessidade.
2. Perfil Motorista
	- Este usuario tem acesso a funcionalidades, como cadastrar viagens, para que os passsageiros possam usar.
3. Perfil Passageiro
	- Este usuario pode buscar e entrar em uma viagem, seja individualmente quanto em grupo.
   
   ### 4. Riscos
Logo abaixo está listado todos os riscos da implementação inicial, podendo ser alterado ou adicionado novos fatores de acordo com o andamento do projeto.

| Data       | Risco                                                                         | Prioridade | Responsável | Status  | Providência/Solução                                                                                         |
| ---------- | ----------------------------------------------------------------------------- | ---------- | ----------- | ------- | ----------------------------------------------------------------------------------------------------------- |
| 28/02/2020 | Não aprendizado das ferramentas utilizadas pelos componentes do grupo a tempo | Alta       | Todos       | Vigente | Reforçar estudos sobre as ferramentas e receber apoio dos integrantes que dominam o mesmo                   |
| 28/02/2020 | Ausência por qualquer motivo do cliente                                       | Média      | Gerente     | Vigente | Planejar o cronograma tendo em base a agenda do cliente e orientar a equipe                                 |
| 28/02/2020 | Divisão de tarefas mal sucedida                                               | Baixa      | Gerente     | Vigente | Acompanhar o desenvolvimento de cada membro da equipe e estimar tempo necessário para conclusão das tarefas |
| 28/02/2020 | Implementação de protótipo com as tecnologias escolhidas pela equipe          | Alta       | Todos       | Vigente | Buscar tutoriais e a documentação das tecnologias para implementar os primeiros casos                       |
   
   ### 5. Suposições e Dependências
A seguir será classificado as suposições presentes no desenvolvimento do projeto, teremos como base a análise de acontecimentos internos e externos, que podem influenciar no andamento do mesmo e que servem de base para o acompanhamento e melhor tomada de decisão do gerente e da divisão de tarefas da equipe de analistas.

1. Tempo
	- Estimar o tempo gasto necessário para conclusão do projeto até o dia da apresentação final no componente curricular e ter atingido a última iteração com sucesso dentro do prazo estabelecido pelo cliente;
2. Recursos
	- Delegar tarefas para não sobrecarregar membros da equipe e fazer reuniões periódicas para acompanhamento do projeto e propor as novas metas a serem alcançadas;
3. Design e desenvolvimento
	- Escolher bem o layout, com base na preferência do cliente, e utilizar as melhores estratégias que as ferramentas de desenvolvimento tenha a oferecer;
4. Tecnologia
	- Aprimorar os conhecimentos na tecnologia escolhida e buscar produtividade com maior rapidez, pois de acordo com a complexidade dos módulos do sistema, a equipe deve estar com o domínio da documentação da linguagem utilizada para melhor suporte e discussão;
5. Qualidade
	- Passar confiança para o cliente, tanto na parte de segurança dos dados até a implementação de uma interface rápida e intuitiva.

A determinação de dependências implica na sequência da execução das atividades e da lógica do negócio. Por isso alguns fatores devem ser discutidos na reunião com o cliente para definição de prioridade dos módulos e da interligação existente entre eles. Será listado as principais dependências e como será feito a análise por parte da gerência para a estratégia de andamento do projeto.

1. Dependências obrigatórias
	- Seguir o modelo conceitual definido pelo contrato, analisar bem os requisitos e as regras de negócio para não entregar um projeto paralelo e que não cumpra com o pré-estabelecido;
2. Dependências arbitradas
	- Uma iteração, dependendo do caso, terá que ser iniciado após a conclusão da anterior;
3. Dependências externas
	- Montar um cronograma para as atividades desenvolvidas no projeto, tendo em vista o cumprimento de outros projetos e avaliações em componentes curriculares diferentes;
4. Dependências internas
	- Ficar atento às regras de negócios e definir bem a cláusula para quando houver solicitação de alteração da lógica de negócio por parte do cliente.
   
   ### 6. Perspectiva do Produto
A perspectiva geral do projeto LocationVAN é otimizar o sistema de lotação de veículos, onde os usuários (que são os clientes do serviço) podem consultar as datas e verificar a disponibilidade de vagas para completar a lotação, dependendo da quantidade de pessoas que precisarem do mesmo. Já no perfil de motorista (responsável pelo serviço), tem acesso ao cadastro e alteração de datas e horários para promoção das viagens, onde estará sendo anexado na base de dados do sistema, permitindo a consulta por parte do usuário e o interesse de fazer o percurso de deslocamento.

O intuito do projeto é promover uma plataforma fluida e fácil de operar, e buscar uma solução viável de rápido acesso, através da internet, para um ramo que movimenta boa parte dos negócios na região.

## 3. Histórico de Revisões


| Data       | Versão | Descrição         | Autor                 |
| ---------- | ------ | ----------------- | --------------------- |
| 28/02/2020 | 0.0.1  | Documento Inicial | **JuremasTEC Social** |
| --/--/2020 |        |                   |                       |
| --/--/2020 |        |                   |                       |
| --/--/2020 |        |                   |                       |
