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
- **[RF003]** - Como secretário, eu gostaria de realizar reagendamentos de consultas por ligação, para que eu possa ajustar a agenda conforme necessário.
- **[RF004]** - Como secretário, eu gostaria de acessar relatórios com o número de atendimentos realizados por período, para apoiar o planejamento e a gestão da equipe.
- **[RF005]** - Como secretário, eu gostaria de cadastrar novos psicólogos no sistema, para manter os dados atualizados conforme a equipe da escola.
- **[RF006]** - Como secretário, eu gostaria de consultar uma lista com os alunos que estão sem atendimento recente, para identificar casos que precisam de acompanhamento contínuo.

## Aluno

- **[RF100]** - Como responsável de um aluno, eu gostaria de agendar consultas psicológicas, para que eu possa garantir o atendimento dele.
- **[RF101]** - Como responsável, eu gostaria de receber lembretes automáticos das consultas agendadas, para que eu não esqueça dos compromissos.
- **[RF102]** - Como responsável, eu gostaria de acessar um histórico resumido dos atendimentos realizados com meu filho, contendo datas e nomes dos profissionais.
- **[RF103]** - Como responsável, eu gostaria de editar ou cancelar agendamentos realizados, para ajustar a agenda da criança conforme imprevistos.
- **[RF104]** - Como responsável, eu gostaria de visualizar o perfil básico dos psicólogos disponíveis, para que eu possa escolher o profissional mais adequado.


## Psicólogo

- **[RF200]** - Como psicólogo, eu gostaria de cadastrar meus horários disponíveis no sistema, inserindo que horas inicio e que horas finalizo meus atendimentos na escola, para que os usuários comuns consigam visualizá-los facilmente.
- **[RF201]** - Como psicólogo, eu gostaria de acessar o histórico completo de atendimentos de cada aluno, para que eu possa acompanhar a evolução dos casos.
- **[RF202]** - Como psicólogo, eu gostaria de registrar anotações privadas em cada atendimento, para manter observações relevantes e confidenciais sobre o paciente.
- **[RF203]** - Como psicólogo, eu gostaria de visualizar minha agenda de atendimentos por semana ou por dia, para facilitar minha organização.
- **[RF204]** - Como psicólogo, eu gostaria de cancelar atendimentos quando necessário, para que o responsável seja automaticamente notificado e a agenda fique atualizada.
- **[RF205]** - Como psicólogo, eu gostaria de ser notificado com antecedência sobre os atendimentos agendados, para que eu possa me preparar adequadamente antes das sessões.
- **[RF206]** - Como psicólogo, eu gostaria de exportar ou imprimir um relatório de atendimentos por aluno, para fins de acompanhamento, reuniões pedagógicas ou encaminhamentos externos.

## Admin do sistema

- **[RF300]** - Como administrador, eu gostaria de gerenciar os perfis de acesso ao sistema, para garantir a segurança e o controle adequado de permissões.
- **[RF301]** - Como administrador, eu gostaria de visualizar estatísticas gerais do sistema, como número de atendimentos e usuários ativos, para auxiliar na tomada de decisões.


# Requisitos não-funcionais

Os requisitos não-funcionais são descritos a seguir.

## Disponibilidade



## Privacidade e segurança



## Usabilidade


## Suportabilidade


## Interoperabilidade


## Manutenibilidade


## Desempenho


## Implementação


## Implantação



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