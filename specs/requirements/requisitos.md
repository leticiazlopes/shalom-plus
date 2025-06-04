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

- **[RNF000]** - ...

## Aluno

- **[RNF100]** - ...

## Psicólogo

- **[RNF200]** - ...

## Admin do sistema

- **[RNF300]** - ...




- **[RF001]** - Como psicólogo, eu gostaria de cadastrar meus horários disponíveis no sistema, inserindo que horas inicio e que horas finalizo meus atendimentos na escola, para que os usuários comuns consigam visualizá-los facilmente.
- **[RF002]** - Como responsável de um aluno, eu gostaria de agendar consultas psicológicas, para que eu possa garantir o atendimento dele.
- **[RF003]** - Como secretário, eu gostaria de conferir as sessões que já estão agendadas, para que eu possa ter uma visão geral da carga de trabalho dos psicólogos e da agenda da escola.
- **[RF004]** - Como secretário, eu gostaria de agendar consultas para que eu possa auxiliar algum responsável que venha a ter alguma dificuldade com o agendamento.
- **[RF005]** - Como secretário, eu gostaria de realizar reagendamentos de consultas por ligação, para que eu possa ajustar a agenda conforme necessário.
- **[RF006]** - 
- **[RF007]** - 
- **[RF008]** -
- **[RF009]** - ...
- **[RF010]** - ...
- **[RF011]** - ...
- **[RF012]** - ...
- **[RF013]** - ...
- **[RF014]** - ...
- **[RF015]** - ...
- **[RF016]** - Como psicólogo, eu gostaria de acessar o histórico completo de atendimentos de cada aluno, para que eu possa acompanhar a evolução dos casos.
- **[RF017]** - Como psicólogo, eu gostaria de registrar anotações privadas em cada atendimento, para manter observações relevantes e confidenciais sobre o paciente.
- **[RF018]** - Como psicólogo, eu gostaria de visualizar minha agenda de atendimentos por semana ou por dia, para facilitar minha organização.
- **[RF019]** - Como psicólogo, eu gostaria de cancelar atendimentos quando necessário, para que o responsável seja automaticamente notificado e a agenda fique atualizada.
- **[RF020]** - Como responsável, eu gostaria de receber lembretes automáticos das consultas agendadas, para que eu não esqueça dos compromissos.
- **[RF021]** - Como responsável, eu gostaria de acessar um histórico resumido dos atendimentos realizados com meu filho, contendo datas e nomes dos profissionais.
- **[RF022]** - Como responsável, eu gostaria de editar ou cancelar agendamentos realizados, para ajustar a agenda da criança conforme imprevistos.
- **[RF023]** - Como responsável, eu gostaria de visualizar o perfil básico dos psicólogos disponíveis, para que eu possa escolher o profissional mais adequado.
- **[RF024]** - Como secretário, eu gostaria de acessar relatórios com o número de atendimentos realizados por período, para apoiar o planejamento e a gestão da equipe.
- **[RF025]** - Como secretário, eu gostaria de cadastrar novos psicólogos no sistema, para manter os dados atualizados conforme a equipe da escola.
- **[RF026]** - Como administrador, eu gostaria de gerenciar os perfis de acesso ao sistema, para garantir a segurança e o controle adequado de permissões.
- **[RF027]** - Como administrador, eu gostaria de visualizar estatísticas gerais do sistema, como número de atendimentos e usuários ativos, para auxiliar na tomada de decisões.
- **[RF028]** - Como psicólogo, eu gostaria de ser notificado com antecedência sobre os atendimentos agendados, para que eu possa me preparar adequadamente antes das sessões.
- **[RF029]** - Como secretário, eu gostaria de consultar uma lista com os alunos que estão sem atendimento recente, para identificar casos que precisam de acompanhamento contínuo.
- **[RF030]** - Como psicólogo, eu gostaria de exportar ou imprimir um relatório de atendimentos por aluno, para fins de acompanhamento, reuniões pedagógicas ou encaminhamentos externos.
- **[RF031]** - ...
- **[RF032]** - ...
- **[RF033]** - ...
- **[RF034]** - ...
- **[RF035]** - ...
- **[RF036]** - ...
- **[RF037]** - ...
- **[RF038]** - ...
- **[RF039]** - ...
- **[RF040]** - ...
- **[RF041]** - ...
- **[RF042]** - ...
- **[RF043]** - ...
- **[RF044]** - ...
- **[RF045]** - ...
- **[RF046]** - ...
- **[RF047]** - ...
- **[RF048]** - ...
- **[RF049]** - ...
- **[RF050]** - ...
- **[RF051]** - ...
- **[RF052]** - ...
- **[RF053]** - ...
- **[RF054]** - ...
- **[RF055]** - ...
- **[RF056]** - ...
- **[RF057]** - ...
- **[RF058]** - ...
- **[RF059]** - ...
- **[RF060]** - ...

# Requisitos não-funcionais

Os requisitos não-funcionais são descritos a seguir.

## Disponibilidade

- **[RNF001]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma.
- **[RNF011]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo com conexão offline, e com posterior sincronização dos dados com o servidor.
- **[RNF012]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.
- **[RNF013]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.

## Privacidade e segurança

- **[RNF002]** - O sistema deve ser desenvolvido de forma que os dados dos clientes sejam protegidos e não sejam acessíveis por terceiros.
- **[RNF003]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados).
- **[RNF014]** - O sistema deve ser desenvolvido de forma que os dados pessoais dos clientes sejam criptografados, como endereço de e-mail, senha, nome completo, cidade e estado. A criptografia deverá ser realizada com o algoritmo SHA-512, e deve impossibilitar a recuperação dos dados originais.

## Usabilidade

- **[RNF004]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento para utilizá-lo.
- **[RNF019]** - O sistema deve ser desenvolvido de forma que possa ser acessado por pessoas com deficiência visual, auditiva e física.

## Suportabilidade

- **[RNF005]** - O sistema deve ser desenvolvido de forma que possa ser executado nos três principais navegadores da web: Google Chrome, Mozilla Firefox e Microsoft Edge através de um computador com sistema operacional Windows, Linux ou Mac OS, bem como tablets e smartphones com sistema operacional Android ou iOS.
- **[RNF006]** - O sistema deve ser desenvolvido de forma que possa ser executado em aplicativos nativos para Android e iOS.

## Interoperabilidade

- **[RNF007]** - O sistema deve ser desenvolvido de forma que possa ser integrado com a API do Google para autenticação de usuários.

## Manutenibilidade

- **[RNF008]** - O sistema deve ser desenvolvido de forma que possa ser facilmente atualizado e mantido, preferencialmente, de maneira automatizada.
- **[RNF009]** - O sistema deve ser desenvolvido de forma que possa ser facilmente testado e validado, de forma manual e automatizada.
- **[RNF016]** - O sistema deve ser documentado de forma que possa ser facilmente compreendido por terceiros e para facilitar a manutenção do sistema.

## Desempenho

- **[RNF010]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo com conexão à internet, com velocidade de conexão de no mínimo 1 Mbps com tempo de resposta de no máximo 5 segundos.

## Implementação

- **[RNF015]** - O sistema deve ser desenvolvido com APIs de acesso aos dados, para que possa ser integrado com outros sistemas.

## Implantação

- **[RNF017]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma de software atualizada.
- **[RNF018]** - O sistema deve ser desenvolvido de forma que possa ser implantado em plataformas de hardware x64 e ARM64, com arquitetura mínima de 64 bits.
- **[RNF020]** - O sistema deve ser verificado quanto ao desempenho mínimo tolerado dos lados servidor e clientes. As especificações sobre pré-requisitos de hardware e software para a execução do sistema devem ser apresentadas em uma página de pré-requisitos, que deve ser acessível a partir do rodapé do site.

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