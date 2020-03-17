# Descrição

O presente documento tem como objetivo abordar e detalhar a lista de User Stories do projeto, fazendo relação direta com os requisitos funcionais do escopo do sistema e também dando ênfase a estimativa de tempo dos pontos de função de cada User Story.

## Histórico de revisões

Data | Versão | Descrição |Autor
-- | -- | -- | --
28/02/2020 | 0.0.1 | Documento inicial | JuremasTEC Social
--/--/2020 | | |
--/--/2020 | | |
--/--/2020 | | |

# Lista de User Stories

User Story US01 - Motorista |
-- |
Descrição |
O sistema deve permitir um vínculo de motorista que tem acesso via login e senha. Primeiramente, o usuário tem que fornecer os atributos nome, endereço, email e senha. O email será o login e ele pode registrar-se diretamente no sistema, solicitando permissão de motorista, e aguardar ativação da conta pelo administrador.
Requisitos envolvidos | RF001, RF002, RF003
Prioridade | Essencial
Estimativa | 60,06h (Web) | Tempo Gasto (real): --h
Tamanho Funcional | 21 PF (Contagem estimativa)
Testes de Aceitação (TA) |
-- |
Código | Descrição
TA01.01 | O motorista informa, na tela Registrar, todos os dados para registrar-se corretamente, ao clicar em salvar ele é notificado com uma mensagem de sucesso. Mensagem: “Cadastro realizado com sucesso, aguardando ativação do administrador!”
TA01.02 | O motorista informa, na tela Registrar, os dados para registrar-se incorretamente, ao clicar em salvar ele é notificado com uma mensagem de erro. Mensagem: “Cadastro não realizado, o campo “xxxx” não foi informado corretamente!”
TA01.03 | O motorista informa, na tela Login, os dados para logar corretamente, ao clicar em entrar ele é notificado com uma mensagem de erro. Mensagem: “Usuário (motorista) não ativado, aguardando ativação do administrador!”
