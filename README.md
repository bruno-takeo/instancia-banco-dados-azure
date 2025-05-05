# Documentação de Criação de Instância de Banco de Dados na Azure

Este repositório contém a documentação completa do processo de criação de uma instância de banco de dados na plataforma Microsoft Azure. O objetivo é relatar passo a passo a experiência prática, incluindo instruções, observações e capturas de tela do procedimento.

## 📌 Objetivo

Demonstrar o processo de provisionamento de um banco de dados na Azure, compreendendo:

- Escolha do tipo de banco de dados (ex: SQL Database)
- Criação da instância
- Configuração básica
- Acesso ao banco
- Considerações de segurança e escalabilidade

## 🧰 Pré-requisitos

- Conta ativa na Microsoft Azure
- Navegador atualizado
- Conexão com a internet

## 🛠️ Etapas do Processo

### 1. Acesso ao Portal da Azure

- Acesse [https://portal.azure.com](https://portal.azure.com)
- Faça login com sua conta Microsoft

📸 Imagem: `imagens/01-portal-azure-login.png`

---

### 2. Criação de um Recurso de Banco de Dados

- No menu lateral, clique em "Criar um recurso"
- Selecione "Banco de dados" > "Banco de dados SQL"

📸 Imagem: `imagens/02-criar-recurso-banco.png`

---

### 3. Configuração da Instância

- Nome da instância
- Nome do servidor
- Autenticação
- Região
- Camada de preço

📸 Imagem: `imagens/03-configuracao-inicial.png`

---

### 4. Regras de Firewall e Conexão

- Permitir acesso ao IP atual
- Testar conexão via Azure Data Studio ou Visual Studio Code

📸 Imagem: `imagens/04-configurar-firewall.png`

---

### 5. Finalização e Validação

- Verificar status da instância
- Acessar painel de gerenciamento

📸 Imagem: `imagens/05-instancia-criada.png`

---

## 📝 Observações

- A camada gratuita permite testar recursos limitados do banco
- Para produção, considere segurança avançada e escalabilidade
- Documente os dados de acesso com segurança


## 🎓 Projeto Acadêmico

Este repositório foi desenvolvido como parte do curso Tralhando com Ambiente Cloud na Azure, disponibilizado pela DIO, com o objetivo de exercitar práticas em computação em nuvem e uso de serviços gerenciados.
