# 📱 Diagramação de Classes - iPhone (Java)

Este repositório contém um projeto simples de simulação de funcionalidades de um iPhone usando Programação Orientada a Objetos em **Java**. Ele foi desenvolvido com o objetivo de praticar os principais pilares da POO, como **encapsulamento**, **herança**, **interfaces** e **polimorfismo**.

## 🎯 Objetivo

Modelar um iPhone com funcionalidades básicas, utilizando interfaces para representar comportamentos comuns em dispositivos móveis.

Funcionalidades implementadas:
- Reprodutor Musical
- Aparelho Telefônico
- Navegador de Internet

## 🛠️ Tecnologias e Ferramentas

- Java (versão 8 ou superior)
- IDE recomendada: IntelliJ IDEA, Eclipse ou VSCode com extensão Java

## 📁 Estrutura do Projeto

- `Main.java`: Classe principal que instancia o iPhone e executa os métodos.
- `iPhone.java`: Classe concreta que implementa todas as interfaces.
- `AparelhoTelefonico.java`: Interface para chamadas e mensagens.
- `NavegadorInternet.java`: Interface para navegação web.
- `ReprodutorMusical.java`: Interface para tocar músicas.

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/Jefersonrds/diagramacao-classes-iPhone.git
cd diagramacao-classes-iPhone
```
2. Compile e execute:
```bash
javac Main.java iphone/*.java
java Main
```
Ou use sua IDE para executar o arquivo `Main.java`.

## 🧠 Conceitos Utilizados

- Interfaces em Java
- Implementação múltipla de interfaces
- Organização modular do código
- Simulação de comportamentos com System.out.println
