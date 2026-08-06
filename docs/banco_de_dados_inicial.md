#  Banco de Dados Inicial — Projeto Aurora

## Objetivo

Definir a estrutura inicial das informações que serão armazenadas pelo Aurora.

O banco de dados deve permitir organizar a jornada do usuário, mantendo suas informações de acompanhamento de forma segura e estruturada.

---

# Entidade: Usuário

## Objetivo:

Armazenar informações básicas da pessoa que utiliza o Aurora.

## Campos:

- ID do usuário.
- Nome.
- E-mail.
- Foto de perfil.
- Idade.
- Data de criação da conta.

---

# Entidade: Perfil de Saúde

## Objetivo:

Armazenar informações relacionadas ao acompanhamento do usuário.

## Campos:

- ID do perfil.
- ID do usuário.
- Condição acompanhada.
- Momento da jornada.
- Possui acompanhamento médico.
- Uso de medicamentos contínuos.

---

# Entidade: Sintomas

## Objetivo:

Registrar sintomas percebidos pelo usuário.

## Campos:

- ID do sintoma.
- ID do usuário.
- Data do registro.
- Tipo de sintoma.
- Intensidade.
- Observações.

---

# Entidade: Medicamentos

## Objetivo:

Organizar medicamentos informados pelo usuário.

## Campos:

- ID do medicamento.
- ID do usuário.
- Nome.
- Horário.
- Frequência.
- Observações.

---

# Entidade: Consultas

## Objetivo:

Registrar consultas e acompanhamentos.

## Campos:

- ID da consulta.
- ID do usuário.
- Especialidade.
- Data.
- Horário.
- Observações.

---

# Entidade: Exames

## Objetivo:

Registrar informações sobre exames realizados.

## Campos:

- ID do exame.
- ID do usuário.
- Tipo de exame.
- Data.
- Observações.

---

# Entidade: Linha do Tempo

## Objetivo:

Centralizar acontecimentos importantes da jornada.

## Campos:

- ID do evento.
- ID do usuário.
- Tipo de evento.
- Data.
- Descrição.

Exemplos:

- Sintoma.
- Consulta.
- Exame.
- Internação.

---

# Entidade: Relatório de Período

## Objetivo:

Gerar um resumo organizado entre datas selecionadas.

## Campos:

- ID do relatório.
- ID do usuário.
- Data inicial.
- Data final.
- Registros relacionados.

---

# Relacionamentos principais

Usuário

⬇️ possui

Perfil de Saúde

⬇️ possui

Sintomas

Medicamentos

Consultas

Exames

Linha do Tempo

Relatórios

---

# Observação

Esta é uma estrutura inicial e poderá ser ajustada conforme o desenvolvimento do projeto.

---

# Status

🌱 Modelo inicial do banco de dados definido.

