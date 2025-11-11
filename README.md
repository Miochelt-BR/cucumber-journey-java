# cucumber-journey-java
# 🥒 Aprendendo BDD com Cucumber em Java

Este repositório foi criado para documentar minha jornada de aprendizado em **BDD (Behavior Driven Development)** utilizando o **Cucumber com Java**.  
O objetivo é compreender como escrever **testes automatizados baseados em comportamento**, conectando especificações em linguagem natural com código Java.

---

## 🎯 Objetivo

Aprender passo a passo:
- Conceitos básicos de **BDD**
- Estrutura de **features (.feature)**
- Criação de **step definitions** em Java
- Execução de testes com **JUnit 5**
- Melhores práticas de organização de testes

---

## 🧩 Tecnologias Utilizadas

- ☕ **Java 25**
- 🥒 **Cucumber 7.18.0**
- ⚙️ **JUnit 5**
- 🧰 **Maven**
- 💻 **IntelliJ IDEA**

---

## 🧠 Conceito Rápido

O **BDD (Behavior Driven Development)** é uma extensão do TDD (Test Driven Development),  
onde os testes são escritos de forma que qualquer pessoa (técnica ou não) possa entender o comportamento do sistema.  

Os testes são descritos em **Gherkin**, uma linguagem simples e legível:

```gherkin
Funcionalidade: aprender cucumber

Cenário: deve executar a especificação
  Dado que cria arquivo corretamente
  Quando quando executa-lo
  Então a especificacao deve finalizar com sucesso
