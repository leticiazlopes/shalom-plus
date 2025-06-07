# Capa

---

<h1>Requisitos de Software</h1>

<h2>Sistema de Controle de Garantias de Produtos (SCGP)</h2>

<small>Versão 1.0</small>

---

## Histórico de revisões

|    Data    | Versão |          Descrição          |      Autor       |
| :--------: | :----: | :-------------------------: | :--------------: |
| 09/06/2025 |  1.0   |    Criação do documento     | Laila de Aquino, Letícia Lopes, Luan Pimenta e Suetone Carneiro |


---

## Sumário

- [Capa](#capa)
  - [Histórico de revisões](#histórico-de-revisões)
  - [Sumário](#sumário)
- [Introdução](#introdução)
  - [Definições, Acrônimos e Abreviações](#definições-acrônimos-e-abreviações)
- [Usuários identificados](#usuários-identificados)
- [Requisitos funcionais](#requisitos-funcionais)
- [Requisitos não-funcionais](#requisitos-não-funcionais)
  - [Disponibilidade](#disponibilidade)
  - [Privacidade e segurança](#privacidade-e-segurança)
  - [Usabilidade](#usabilidade)
  - [Suportabilidade](#suportabilidade)
  - [Interoperabilidade](#interoperabilidade)
  - [Manutenibilidade](#manutenibilidade)
  - [Desempenho](#desempenho)
  - [Implementação](#implementação)
  - [Implantação](#implantação)
- [Matriz de rastreabilidade](#matriz-de-rastreabilidade)
  - [Rastreabilidade entre NFs e RNFs](#rastreabilidade-entre-nfs-e-rnfs)

---

# Introdução

O objetivo deste documento é apresentar os requisitos de software do produto **Shalom+**

## Definições, Acrônimos e Abreviações

Esta subseção fornece as definições de todos os termos, acrônimos e abreviações necessárias à adequada interpretação do Documento de Requisitos.

- Identificação dos requisitos: por convenção, a referência a requisitos é feita através do identificador de requisitos, de acordo como descrito abaixo:

  `[IDENTIFICADOR DO TIPO DE REQUISITOSidentificador do requisito]`

  O identificador do tipo de requisitos é conforme abaixo:

  - RF – Requisito Funcional
  - RNF – Requisito Não-Funcional
  - NR – Não-Requisito

  O identificador do requisito será uma sequência numérica. Esse número sequencial será único para todo o conjunto de tipos de requisitos.

  **Exemplo**: RF0001, RF1234, RNF1234, NR1212

- Atributos dos Requisitos: os atributos de requisitos estabelecidos são:
  - **Requisitos vinculados**: fornece uma lista dos requisitos que mantém rastreabilidade.
  - **Prioridade**: Essencial, Importante, Desejável
  - **Complexidade**: Complexa, Alta, Média ou Baixa.
  - **Risco**: Alto, Médio, Baixo

# Usuários identificados

Os seguintes usuários foram identificados para o sistema:

- Usuário do sistema
  - Usuários comuns
    - Psicólogo
    - Responsável pelo aluno
    - Secretário
  - Administrador do sistema

# Requisitos funcionais

Os requisitos funcionais são descritos a seguir, organizados por perfil de usuário:

## Secretário

- **[RF001]** - Como secretário, eu gostaria de conferir as sessões que já estão agendadas, para que eu possa ter uma visão geral da carga de trabalho dos psicólogos e da agenda da escola.
- **[RF002]** - Como secretário, eu gostaria de agendar consultas para que eu possa auxiliar algum responsável que venha a ter alguma dificuldade com o agendamento.
- **[RF003]** - Como secretário, eu gostaria de realizar reagendamentos de consultas solicitadas por ligação, para que eu possa ajustar a agenda conforme necessário.
- **[RF004]** - Como secretário, eu gostaria de acessar relatórios com o número de atendimentos realizados por período, para apoiar o planejamento e a gestão da equipe.
- **[RF005]** - Como secretário, eu gostaria de acessar o sistema por meio de login e senha pessoais, para garantir a segurança e a individualização das ações feitas no sistema.
- **[RF006]** - Como secretário, eu gostaria de redefinir minha senha de acesso caso esqueça, usando um canal como o e-mail, para não perder acesso ao sistema.
- **[RF007]** - Como secretário, eu gostaria de visualizar listas de atendimento diárias ou semanais por psicólogo, para facilitar a impressão ou o acompanhamento físico, quando necessário.
- **[RF008]** - Como secretário, eu gostaria de visualizar detalhes de cada agendamento (como horário, nome do aluno, responsável, observações), para confirmar e repassar essas informações se necessário.
- **[RF009]** - Como secretário, eu gostaria de visualizar a agenda em formato de calendário com cores diferentes para cada psicólogo para facilitar a leitura visual.
- **[RF010]** - Como secretário, eu gostaria de aplicar filtros por psicólogo, turma ou aluno na agenda, para localizar atendimentos específicos com mais agilidade.
- **[RF011]** - Como secretário, eu gostaria que a agenda exibisse também os atendimentos emergenciais aprovados, para manter uma visão completa dos compromissos do psicólogo.
- **[RF012]** - Como secretário, eu gostaria de receber notificações sobre cancelamentos ou alterações feitas por responsáveis ou psicólogos, para manter a agenda sempre atualizada.
- **[RF013]** - Como secretário, eu gostaria que o sistema permitisse buscas rápidas por nome do responsável ou aluno, para encontrar informações sem perder tempo.
- **[RF014]** - Como secretário, eu gostaria de enviar comunicados e avisos importantes para os responsáveis, para manter todos informados sobre mudanças e eventos.


## Aluno

- **[RF100]** - Como responsável de um aluno, eu gostaria de agendar consultas psicológicas, para que eu possa garantir o atendimento dele.
- **[RF101]** - Como responsável, eu gostaria de receber lembretes automáticos das consultas agendadas, para que eu não esqueça dos compromissos.
- **[RF102]** - Como responsável, eu gostaria de acessar um histórico resumido dos atendimentos realizados com meu filho, contendo datas e nomes dos profissionais.
- **[RF103]** - Como responsável, eu gostaria de editar ou cancelar agendamentos realizados, para ajustar a agenda da criança conforme imprevistos.
- **[RF104]** - Como responsável, eu gostaria de visualizar o perfil básico dos psicólogos disponíveis, para que eu possa escolher o profissional mais adequado.
- **[RF105]** - Como responsável, eu gostaria de atualizar meus dados de contato no sistema, para garantir que as informações estejam sempre corretas.
- **[RF106]** - Como responsável, eu gostaria de receber notificações sobre alterações nos agendamentos, para me manter informado.
- **[RF107]** - Como responsável, eu gostaria de receber avisos em caso de ausência do psicólogo, para me organizar com antecedência.
- **[RF108]** - Como responsável, eu gostaria de receber um resumo mensal das consultas realizadas, para acompanhar com clareza o progresso do acompanhamento psicológico.
- **[RF109]** - Como responsável, eu gostaria de poder recuperar a minha senha facilmente, para não perder o acesso ao sistema.
- **[RF110]** - Como responsável, eu gostaria de registrar informações importantes sobre o aluno (alergias, necessidades especiais, rotinas), para auxiliar os profissionais no cuidado.
- **[RF111]** - Como responsável, eu gostaria de acessar orientações passadas pelo psicólogo após cada sessão, para acompanhar e aplicar recomendações em casa.
- **[RF112]** - Como responsável, eu gostaria de visualizar o status dos atendimentos solicitados (pendente, confirmado, concluído, cancelado), para acompanhamento claro.
- **[RF113]** - Como responsável, eu gostaria de ter acesso a um canal de suporte no sistema, para tirar dúvidas sobre o uso da plataforma ou sobre o atendimento.
- **[RF114]** - Como responsável, eu gostaria que o sistema tivesse ícones ilustrativos e coloridos nos botões principais, para facilitar a navegação mesmo sem leitura.


## Psicólogo


- **[RF200]** - Como psicólogo, eu gostaria de acessar o sistema por meio de login e senha pessoais, para garantir segurança e privacidade dos meus dados e dos atendimentos.  
- **[RF201]** - Como psicólogo, eu gostaria de redefinir minha senha de acesso por e-mail ou outro canal seguro, caso eu esqueça, para não perder o acesso ao sistema.  
- **[RF202]** - Como psicólogo, eu gostaria que meu login expirasse automaticamente após um tempo de inatividade, para proteger os dados em dispositivos compartilhados.  
- **[RF203]** - Como psicólogo, eu gostaria que o sistema exigisse autenticação para acessar áreas sensíveis, como prontuários e anotações privadas, para garantir a confidencialidade das informações.  
- **[RF204]** - Como psicólogo, eu gostaria de cadastrar meus horários disponíveis no sistema, inserindo que horas inicio e que horas finalizo meus atendimentos na escola, para que os usuários comuns consigam visualizá-los facilmente.  
- **[RF205]** - Como psicólogo, eu gostaria de acessar o histórico completo de atendimentos de cada aluno, para que eu possa acompanhar a evolução dos casos.  
- **[RF206]** - Como psicólogo, eu gostaria de registrar anotações privadas em cada atendimento, para manter observações relevantes e confidenciais sobre o paciente.  
- **[RF207]** - Como psicólogo, eu gostaria de visualizar minha agenda de atendimentos por semana ou por dia, para facilitar minha organização.  
- **[RF208]** - Como psicólogo, eu gostaria que o cancelamento de agendamentos emitisse notificações, para que o responsável seja automaticamente notificado e a agenda fique atualizada.  
- **[RF209]** - Como psicólogo, eu gostaria de ser notificado com antecedência sobre os atendimentos agendados, para que eu possa me preparar adequadamente antes das sessões.  
- **[RF210]** - Como psicólogo, eu gostaria de exportar ou imprimir um relatório de atendimentos por aluno, para fins de acompanhamento, reuniões pedagógicas ou encaminhamentos externos.  
- **[RF211]** - Como psicólogo, eu gostaria de registrar informações sobre o comparecimento do aluno (presente, ausente, reagendado), para manter o histórico de frequência.  
- **[RF212]** - Como psicólogo, eu gostaria de ter acesso ao perfil completo do aluno (nome, idade, turma, responsável), para contextualizar os atendimentos.  
- **[RF213]** - Como psicólogo, eu gostaria de anexar arquivos aos registros dos atendimentos (ex: relatórios, laudos, atividades), para manter toda a documentação centralizada.  
- **[RF214]** - Como psicólogo, eu gostaria de pesquisar atendimentos por nome do aluno, data, turma ou palavras-chave, para encontrar registros com mais agilidade.  
- **[RF215]** - Como psicólogo, eu gostaria de receber notificações quando um atendimento emergencial for solicitado por outro usuário, para que eu possa analisar e agir com rapidez.  
- **[RF216]** - Como psicólogo, eu gostaria que as solicitações de atendimento emergencial permitissem anexos (como relatórios, observações escritas ou fotos autorizadas), para que eu possa ter mais contexto antes de aceitar ou recusar a solicitação.  
- **[RF217]** - Como psicólogo, eu gostaria que cada solicitação de atendimento emergencial ficasse registrada com data, hora, solicitante e status, para fins de histórico e análise posterior.  


## Admin do sistema

- **[RF300]** - Como administrador, eu gostaria de gerenciar os perfis de acesso ao sistema, para garantir a segurança e o controle adequado de permissões.
- **[RF301]** - Como administrador, eu gostaria de editar dados cadastrais de qualquer usuário, para corrigir erros ou atualizações necessárias.
- **[RF302]** - Como um administrador, eu gostaria de verificar o funcionamento geral da aplicação, para que eu possa garantir a estabilidade do sistema.
- **[RF303]** - Como um administrador, eu gostaria de visualizar logs de atividades de todos os usuários, para que eu possa auditar o uso do sistema e identificar possíveis anomalias.
- **[RF304]** - Como administrador, eu gostaria de realizar o backup e a restauração de dados do sistema, para que eu possa garantir a recuperação de informações em caso de falhas.
- **[RF305]** - Como administrador, eu gostaria de gerenciar as configurações de segurança do sistema, como políticas de senha e autenticação de dois fatores, para que eu possa reforçar a proteção dos dados.
- **[RF306]** - Como administrador, eu gostaria de receber alertas automáticos sobre erros críticos no sistema (falhas de autenticação, tempo de resposta elevado, erros nas requisições), para agir rapidamente.
- **[RF307]** - Como administrador, eu gostaria de visualizar estatísticas gerais do sistema, como número de atendimentos e usuários ativos, para auxiliar na tomada de decisões.
- **[RF308]** - Como administrador, eu gostaria de configurar os horários de funcionamento padrão da escola, para que o sistema respeite esses parâmetros ao permitir agendamentos.
- **[RF309]** - Como administrador, eu gostaria de enviar e gerenciar comunicados gerais ou avisos de manutenção para todos os usuários do sistema, para que eu possa manter o usuário comum informado.
- **[RF310]** - Como administrador, eu gostaria de auditar acessos a dados sensíveis (como prontuários e laudos), registrando quem acessou, quando e por qual motivo, para fins de conformidade com a LGPD.
- **[RF311]** - Como administrador, eu gostaria de realizar testes de desempenho periodicamente, para verificar se o sistema está operando dentro dos padrões definidos.
- **[RF312]** - Como administrador, eu gostaria de receber solicitações dos usuários para correções e melhorias no sistema, para garantir uma melhoria contínua do produto.
- **[RF313]** - Como administrador, eu gostaria de visualizar solicitações de suporte técnico feitas pelos usuários, para que eu possa monitorar e priorizar correções e melhorias.
- **[RF314]** - Como adiministrador, eu gostaria de acessar um ambiente de homologação, para validar atualizações e melhorias do sistema juntamente ao cliente.

# Requisitos não-funcionais

Os requisitos não-funcionais são descritos a seguir.

## Disponibilidade
- **[RNF001]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.
- **[RNF002]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.



## Privacidade e segurança
- **[RNF003]** - O sistema deve criptografar todas as comunicações com o servidor por meio de HTTPS, garantindo que dados sensíveis não sejam interceptados durante a transmissão.
- **[RNF004]** - O acesso a informações sensíveis, como prontuários e anotações privadas, deve ser restrito a usuários autenticados com permissão específica, prevenindo acessos indevidos.



## Usabilidade
- **[RNF005]** - O sistema deve apresentar uma interface intuitiva e responsiva, com linguagem acessível e ícones autoexplicativos, para garantir que usuários com baixa familiaridade com tecnologia consigam utilizá-lo com facilidade.
- **[RNF006]** - A navegação no sistema deve ser consistente e previsível em todas as telas, com elementos de interface como menus, botões e breadcrumbs, sempre localizados em posições de fácil visualização, para facilitar o aprendizado e a familiarização.
- **[RNF007]** - O sistema deve disponibilizar feedbacks imediatos (ex: mensagens de confirmação ou erro) após cada ação do usuário, para garantir que ele entenda o que ocorreu e saiba qual será o próximo passo.


## Suportabilidade
- **[RNF007]** -  sistema deve ser desenvolvido de forma que possa ser executado nos dois principais navegadores da web: Google Chrome e Mozilla Firefox através de um computador com sistema operacional Windows, Linux ou Mac OS, bem como tablets e smartphones com sistema operacional Android ou iOS.
- **[RNF008]** - O sistema deve permitir a aplicação de atualizações de segurança e correções de bugs sem interrupção total do serviço.


## Interoperabilidade
- **[RNF009]** - O sistema deve ser capaz de exportar os dados sobre os horários e perfis dos psicólogos em PDF para impressão e exposição na escola.
- **[RNF010]** - O sistema deve utilizar o protocolo HTTPS em todas as integrações com serviços externos, garantindo comunicação segura.


## Manutenibilidade
- **[RNF011]** - O sistema deve ser desenvolvido com um código-fonte bem documentado, facilitando a manutenção, correções e adição de novas funcionalidades
- **[RNF012]** - O sistema deve permitir a aplicação de atualizações e correções sem necessidade de interrupção total do serviço, minimizando o impacto para os usuários


## Desempenho
- **[RNF013]** - O sistema deve ser capaz de suportar múltiplos usuários simultâneos sem degradação perceptível no desempenho.
- **[RNF014]** - O tempo de carregamento da interface inicial deve ser inferior a 3 segundos em conexões padrão(4G ou Wifi), garantindo uma experiência de uso fluida e responsiva.


## Implementação
- **[RNF015]** - O sistema deve ser desenvolvido para ser acessado por meio da internet, utilizando infraestrutura em nuvem pública para hospedagem e armazenamento de dados.
- **[RNF016]** - O sistema deve permitir comunicação com o servidor via protocolo HTTP, garantindo a troca segura de informações entre os dispositivos dos usuários e o servidor.

## Implantação
- **[RNF017]** - O sistema deve ser configurado pela equipe técnica da empresa desenvolvedora, sendo disponibilizado em ambiente online com login e senha para cada cliente.
- **[RNF018]** - O sistema deve permitir funcionamento em navegadores web modernos e dispositivos móveis, sem necessidade de instalação local nos dispositivos dos usuários.

# Matriz de rastreabilidade

A matriz de rastreabilidade é apresentada a seguir.

## Rastreabilidade entre NFs e RNFs

| RF / RNF | RF001 | RF002 | RF003 | RF004 | RF005 | RF006 | RF007 | RF008 | RF009 | RF010 | RF011 | RF012 | RF013 | RF014 | RF015 | RF016 | RF017 | RF018 | RF019 | RF020 | RF021 | RF022 |
| :------: | :---: | :---: | :---: | :---: | :---: | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  RNF001  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF002  |       |       |   X   |   X   |   X   |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF003  |       |       |   X   |   X   |   X   |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF004  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF005  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF006  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF007  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF008  |       |       |       |       |       |       |       |       |       |       |       |       |       |       | X     |       |       |       |       |       |       |       |
|  RNF009  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF010  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF011  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF012  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF013  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |
|  RNF014  |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       |       | X     | X     | X     | X     | X     |

Criado em Abril de 2023 por _Maxwell Anderson_