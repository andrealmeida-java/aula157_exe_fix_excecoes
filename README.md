# Bank Account Domain

Projeto em Java que simula operações básicas de uma conta bancária, com foco em
modelagem de domínio, encapsulamento e tratamento de exceções personalizadas.

## 📌 Objetivo
Demonstrar boas práticas de Programação Orientada a Objetos em Java, incluindo:
- Encapsulamento
- Validação de regras de negócio
- Exceções de domínio (`DomainException`)
- Separação por camadas (application / model)

## 🛠️ Tecnologias utilizadas
- Java 21
- Programação Orientada a Objetos
- Exceções personalizadas

## 📂 Estrutura do projeto
```
src/
 ├── application
 │   └── Program.java
 └── model
     ├── entities
     │   └── Account.java
     └── exception
         └── DomainException.java
```
## 🚀 Funcionalidades
- Criar conta bancária
- Depósito com validação
- Saque respeitando:
  - Saldo disponível
  - Limite de saque
- Tratamento de erros de domínio

## ⚠️ Regras de negócio
- Não é permitido sacar valor maior que o saldo
- Não é permitido sacar valor maior que o limite
- Valores negativos ou zero são inválidos

## ▶️ Como executar
1. Clone o repositório
2. Compile o projeto
3. Execute a classe `Program`

## 📚 Aprendizados
Este projeto reforça conceitos fundamentais de Java e serve como base para
evoluções futuras, como testes automatizados e APIs REST com Spring Boot.
