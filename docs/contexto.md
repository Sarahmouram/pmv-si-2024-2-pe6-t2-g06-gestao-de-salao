# Introdução

Texto descritivo com a visão geral do projeto abordado. Inclui o contexto, o problema, os objetivos, a justificativa e o público-alvo do projeto.

## Problema
Nesse momento você deve apresentar o problema que a sua aplicação deve  resolver. No entanto, não é a hora de comentar sobre a aplicação.

Descreva também o contexto em que essa aplicação será usada, se  houver: empresa, tecnologias, etc. Novamente, descreva apenas o que de  fato existir, pois ainda não é a hora de apresentar requisitos  detalhados ou projetos.

Nesse momento, o grupo pode optar por fazer uso  de ferramentas como Design Thinking, que permite um olhar de ponta a ponta para o problema.

> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos

Aqui você deve descrever os objetivos do trabalho indicando que o objetivo geral é desenvolver um software para solucionar o problema apresentado acima. 

Apresente também alguns (pelo menos 2) objetivos específicos dependendo de onde você vai querer concentrar a sua prática investigativa, ou como você vai aprofundar no seu trabalho.
 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

Descreva a importância ou a motivação para trabalhar com esta aplicação que você escolheu. Indique as razões pelas quais você escolheu seus objetivos específicos ou as razões para aprofundar em certos aspectos do software.

O grupo de trabalho pode fazer uso de questionários, entrevistas e dados estatísticos, que podem ser apresentados, com o objetivo de esclarecer detalhes do problema que será abordado pelo grupo.

> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Descreva quem serão as pessoas que usarão a sua aplicação indicando os diferentes perfis. O objetivo aqui não é definir quem serão os clientes ou quais serão os papéis dos usuários na aplicação. A ideia é, dentro do possível, conhecer um pouco mais sobre o perfil dos usuários: conhecimentos prévios, relação com a tecnologia, relações
hierárquicas, etc.

Adicione informações sobre o público-alvo por meio de uma descrição textual, diagramas de personas e mapa de stakeholders.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)

# Especificações do Projeto

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve exibir uma opção para o usuário selecionar o tipo de conta (Usuário Final, Empresa) antes de realizar o login ou cadastro | TELA DE LOGIN - Seleção do Tipo de Usuário | ALTA |
|RF-002| O cadastro de um novo funcionário/profissional só pode ser realizado após o login de um funcionário autorizado da empresa. | TELA DE LOGIN - Seleção do Tipo de Usuário | ALTA |
|RF-003| O sistema deve permitir que o usuário final, empresa e funcionário entrem com o seu e-mail e senha. | TELA DE LOGIN - Entrada de Credenciais | ALTA |
|RF-004| O sistema deve exibir um botão para visualizar/ocultar a senha digitada. | TELA DE LOGIN - Entrada de Credenciais | ALTA |
|RF-005| O sistema deve permitir que somente um funcionário autorizado da empresa, após fazer login, cadastre novos funcionários/profissionais. | TELA DE LOGIN - Cadastro de Novo Funcionário Após Login de Funcionário Autorizado | ALTA |
|RF-006| O sistema deve exigir que o funcionário autorizado insira os seguintes dados ao cadastrar um novo funcionário/profissional: nome completo do funcionário, e-mail corporativo do funcionário, CPF, telefone, cargo ou especialidade, e CNPJ da empresa. | TELA DE LOGIN - Cadastro de Novo Funcionário Após Login de Funcionário Autorizado | ALTA |
|RF-007| O sistema deve enviar um convite para o e-mail do funcionário cadastrado, contendo um link para a criação de sua senha e ativação da conta. | TELA DE LOGIN - Cadastro de Novo Funcionário Após Login de Funcionário Autorizado | ALTA |
|RF-008| O sistema deve permitir que o funcionário complete seu cadastro e defina sua senha após receber o convite enviado pela empresa. | TELA DE LOGIN - Cadastro de Novo Funcionário Após Login de Funcionário Autorizado | ALTA |
|RF-009| O sistema deve ativar a conta do funcionário apenas após a definição da senha e a confirmação dos dados. | TELA DE LOGIN - Cadastro de Novo Funcionário Após Login de Funcionário Autorizado | ALTA |
|RF-010| |RF-010| AQUI | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA | | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA |
|RF-011| O sistema deve permitir que o funcionário/profissional crie, edite e exclua compromissos em sua agenda pessoal. | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA |
|RF-012| O sistema deve permitir que o funcionário/profissional defina a disponibilidade em sua agenda, indicando horários livres e ocupados. | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA |
|RF-013| O sistema deve garantir que apenas o funcionário/profissional autenticado tenha acesso à sua agenda específica, sem visibilidade das agendas de outros profissionais, exceto pela empresa administradora. | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA |
|RF-014| O sistema deve permitir que o funcionário/profissional visualize e gerencie reservas feitas por usuários finais diretamente em sua agenda | APÓS LOGIN - Gestão de Agendas para funcionário | ALTA |
|RF-015| O sistema deve assegurar que cada funcionário/profissional só possa visualizar e editar a sua própria agenda, sem acesso às agendas de outros profissionais ou à agenda corporativa. | APÓS LOGIN - Controle de Acesso à Agenda para funcionário | ALTA |
|RF-016| O sistema deve permitir que a empresa (ou administradores designados) visualize a disponibilidade e compromissos de todos os funcionários/profissionais, mas sem poder editar suas agendas individuais, a menos que explicitamente autorizado. | APÓS LOGIN - Controle de Acesso à Agenda para funcionário | ALTA |
|RF-017| O sistema deve enviar notificações por e-mail ou WhatsApp para o funcionário/profissional quando um novo compromisso é agendado ou cancelado por um usuário final. | APÓS LOGIN - Notificações para funcionário | BAIXA |
|RF-018| O sistema deve permitir que o funcionário/profissional configure alertas de lembrete para compromissos futuros em sua agenda. | APÓS LOGIN - Notificações para funcionário | BAIXA |
|RF-019| O sistema deve garantir que o acesso a funcionalidades específicas da aplicação seja concedido com base no tipo de usuário (Usuário Final, Empresa ou Funcionário/Profissional). | APÓS LOGIN - Controle de Acesso | ALTA |
|RF-010| O sistema deve bloquear a conta após um número específico de tentativas de login falhas e fornecer instruções para desbloqueio. | APÓS LOGIN - Controle de Acesso | BAIXA |
|RF-010| O sistema deve redirecionar o funcionário/profissional para a tela da agenda pessoal após o login. | APÓS LOGIN - Redirecionamento Pós-Login | ALTA |
|RF-010| O sistema deve redirecionar o usuário final para a tela inicial apropriada após o login (ex.: LISTA DE SALÕES NO RAIO DE 20 KM). | APÓS LOGIN - Redirecionamento Pós-Login | ALTA |
|RF-010| O sistema deve redirecionar a empresa para a tela inicial corporativa após o login (ex.: painel administrativo da empresa). | APÓS LOGIN - Redirecionamento Pós-Login | ALTA |
|RF-010| O sistema deve fornecer uma opção visível para logout em todas as telas pós-login. | LOGOUT | ALTA |
|RF-010| O sistema deve garantir que o logout encerre completamente a sessão do usuário, exigindo novo login para acessar a aplicação novamente. | LOGOUT | ALTA |
|RF-010| O sistema deve exibir mensagens claras e específicas para erros de login, como "Senha incorreta" ou "E-mail não registrado". | LOGIN - Feedback de Erro | ALTA |
|RF-010| O sistema deve alertar o usuário em caso de tentativa de acesso com uma conta incorreta para o tipo de usuário selecionado. | LOGIN - Feedback de Erro | ALTA |
|RF-010| O sistema deve exigir que todos os tipos de usuários aceitem os Termos de Uso e a Política de Privacidade durante o cadastro. | SIGIN - Termos de Uso e Política de Privacidade | BAIXA |
|RF-010| O sistema deve fornecer links para os documentos de Termos de Uso e Política de Privacidade na tela de cadastro. | SIGNIN - Termos de Uso e Política de Privacidade | BAIXA |
|RF-010| O sistema deve fornecer uma opção para o funcionário, usuário final e a empresa solicitarem a recuperação de senha | LOGIN - Recuperação de Senha | BAIXA |
|RF-010| O sistema deve enviar um e-mail ou mensagem via WhatsApp com um link ou código para redefinição de senha. | LOGIN - Recuperação de Senha | BAIXA |
|RF-010| O sistema deve permitir que o funcionário, usuário final e a empresa selecionem a opção "Lembre-me" para manter a sessão ativa, desde que a política de segurança da aplicação permita. | LOGIN - Lembre-me | BAIXA |
|RF-010| O sistema deve permitir que o funcionário cadastre seu endereço completo e outras informações complementares, como CPF. | LOGIN - Cadastro de Endereço e Informações Complementares (Opcional) | BAIXA |
|RF-010| O sistema deve permitir que o usuário final e a empresa cadastrem endereços e outras informações relevantes. | LOGIN - Cadastro de Endereço e Informações Complementares (Opcional) | BAIXA |
|RF-010| AQUI | LOGIN - Cadastro de Endereço e Informações Complementares (Opcional) | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Deve ser desenvolvido uma aplicação web               |
|03| Deve ser desenvolvida uma aplicação mobile            |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

# Catálogo de Serviços

## Serviços Cliente:
### Cadastro/Login:
- Características:

### Agendamentos:
- Características:
  
### Pagamento de serviços:
- Características:

## Serviços Salão
### Cadastro/Login:
- Características:
  
### Controle de agenda:
- Características:

# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

![arq](https://github.com/user-attachments/assets/b9402e05-8445-47c3-9d47-f11696e38a3d)


## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
