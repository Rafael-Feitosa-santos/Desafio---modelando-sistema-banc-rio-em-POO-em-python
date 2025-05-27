# 🏦 Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em Python, com funcionalidades de criação de clientes e contas, realização de depósitos, saques, exibição de extrato e controle de transações. O código segue princípios de orientação a objetos e utiliza abstrações para modelar transações.

---

## 🚀 Funcionalidades

- Criar cliente (Pessoa Física)  
- Criar conta corrente  
- Realizar depósitos  
- Realizar saques com limite de valor e número de saques  
- Consultar extrato bancário  
- Listar contas cadastradas  

---

## 🧱 Estrutura do Projeto

- **Cliente** e **PessoaFisica**: Representam os dados do cliente.  
- **Conta** e **ContaCorrente**: Modelam as contas bancárias.  
- **Transacao**, **Saque** e **Deposito**: Representam as operações bancárias.  
- **Historico**: Armazena as transações realizadas.  
- **Funções auxiliares**: Funções para realizar ações com base em entrada do usuário.  

---

## 📁 Organização de Classes

- **Cliente**: Classe base que representa um cliente genérico.  
- **PessoaFisica**: Subclasse de Cliente, adiciona atributos como nome, data_nascimento e cpf.  
- **Conta**: Classe base de conta bancária, com métodos para sacar, depositar e controle de saldo.  
- **ContaCorrente**: Subclasse de Conta, adiciona regras de limite de saque e número de saques.  
- **Transacao** (abstract): Interface para operações.  
- **Saque** e **Deposito**: Implementações de Transacao.  
- **Historico**: Armazena todas as transações com data/hora.  

---

## 📋 Menu Principal

Ao executar o programa, um menu interativo é exibido com as seguintes opções:


---

## 🧪 Exemplo de Uso

- Crie um novo usuário `[nu]`  
- Crie uma nova conta para este usuário `[nc]`  
- Realize depósitos e saques `[d]`, `[s]`  
- Consulte o extrato `[e]`  
- Liste todas as contas `[lc]`  

---

## 📊 Requisitos

- Python 3.10

---

Clone este repositório:

```sh
git clone https://github.com/Rafael-Feitosa-santos/Desafio---modelando-sistema-banc-rio-em-POO-em-python.git
```

