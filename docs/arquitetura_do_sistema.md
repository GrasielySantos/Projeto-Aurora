# Arquitetura Inicial do Sistema — Projeto Aurora

## Objetivo

Definir a estrutura inicial da aplicação Aurora, identificando os principais componentes necessários para o funcionamento do sistema.

A arquitetura será construída pensando em uma aplicação segura, organizada e preparada para futuras evoluções.

---

# Visão geral da arquitetura

O Aurora será composto por:

Usuário  
⬇️  
Interface do aplicativo (Front-end)  
⬇️  
Servidor da aplicação (Back-end)  
⬇️  
Banco de dados  

Serviços complementares:

- Autenticação de usuário.
- Armazenamento de informações.
- Segurança e privacidade.

---

# 1. Usuário

O usuário é o centro da aplicação.

O Aurora será desenvolvido para auxiliar pessoas no acompanhamento da própria rotina de saúde.

Informações principais:

- Nome.
- Idade.
- Condição acompanhada.
- Histórico de acompanhamento.
- Preferências pessoais.

---

# 2. Autenticação

## Objetivo:

Permitir acesso seguro e personalizado ao aplicativo.

## Possibilidades:

- Login com conta Google.
- Login com e-mail e senha.

## Responsabilidades:

- Identificar o usuário.
- Controlar acesso aos dados.
- Manter informações individuais protegidas.

---

# 3. Front-end

## Objetivo:

Responsável pela interface e experiência do usuário.

## Responsabilidades:

- Apresentar as telas do aplicativo.
- Permitir interação do usuário.
- Exibir informações organizadas.

## Principais telas:

- Boas-vindas.
- Login.
- Cadastro.
- Dashboard.
- Sintomas.
- Medicamentos.
- Consultas.
- Linha do tempo.
- Resumo de período.
- Perfil.

---

# 4. Back-end

## Objetivo:

Gerenciar as regras e comunicação da aplicação.

## Responsabilidades:

- Processar informações.
- Gerenciar usuários.
- Organizar registros.
- Controlar acesso aos dados.

---

# 5. Banco de dados

## Objetivo:

Armazenar informações da aplicação de forma organizada.

## Dados previstos:

### Usuários:

- Identificação.
- Perfil.
- Preferências.

### Acompanhamento:

- Sintomas.
- Medicamentos.
- Consultas.
- Exames.
- Internações.
- Eventos da linha do tempo.

### Relatórios:

- Resumos de períodos.
- Histórico de registros.

---

# 6. Segurança e privacidade

O Aurora trabalha com informações pessoais sensíveis.

Princípios:

🔒 Proteção dos dados do usuário.

🔒 Acesso individual às informações.

🔒 Transparência sobre uso dos dados.

🔒 Respeito à privacidade.

---

# 7. Evolução futura

Possíveis integrações:

- Armazenamento de documentos.
- Upload de exames.
- Gráficos de evolução.
- Integração com dispositivos.
- Recursos inteligentes.

---

# Status

🌱 Arquitetura inicial definida.
