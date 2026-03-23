# ♟️ ChessSystem

## 📖 Descrição

O **ChessSystem** é uma aplicação desenvolvida em Java que simula uma partida de xadrez no terminal. O projeto foi construído com foco em aplicar de forma prática os principais conceitos de **Programação Orientada a Objetos (OOP)**, como encapsulamento, herança, polimorfismo e abstração.

O sistema permite que dois jogadores realizem uma partida completa, respeitando as regras oficiais do xadrez, incluindo movimentação das peças, captura, xeque e xeque-mate.

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

* Praticar e consolidar conceitos de **POO em Java**
* Trabalhar com **modelagem de domínio**
* Simular regras reais de um sistema complexo
* Melhorar organização de código e boas práticas
* Servir como projeto de portfólio para desenvolvedor back-end

---

## 🧠 Conceitos de OOP aplicados

### 🔒 Encapsulamento

* Atributos protegidos com modificadores de acesso (`private`, `protected`)
* Controle de acesso através de métodos getters/setters

### 🧬 Herança

* Classe base `Piece`
* Classes específicas como:

  * `King`
  * `Queen`
  * `Rook`
  * `Bishop`
  * `Knight`
  * `Pawn`

### 🎭 Polimorfismo

* Cada peça implementa seu próprio comportamento de movimento
* Sobrescrita de métodos (`override`) para regras específicas

### 🧱 Abstração

* Separação clara entre:

  * Regras do jogo (`ChessMatch`)
  * Tabuleiro (`Board`)
  * Peças (`Piece`)

---

## 🏗️ Estrutura do Projeto

```
src/
│
├── application/
│   └── Program.java
│
├── boardgame/
│   ├── Board.java
│   ├── Piece.java
│   └── Position.java
│
└── chess/
    ├── ChessMatch.java
    ├── ChessPiece.java
    ├── ChessPosition.java
    └── pieces/
        ├── King.java
        ├── Queen.java
        ├── Rook.java
        ├── Bishop.java
        ├── Knight.java
        └── Pawn.java
```

---

## ⚙️ Funcionalidades

* ✔️ Inicialização de uma partida de xadrez
* ✔️ Movimentação de peças
* ✔️ Validação de movimentos
* ✔️ Captura de peças
* ✔️ Controle de turnos
* ✔️ Detecção de **xeque**
* ✔️ Detecção de **xeque-mate**
* ✔️ Exibição do tabuleiro no terminal

---

## 🖥️ Tecnologias Utilizadas

* **Java 17+**
* Programação Orientada a Objetos (OOP)
* Console (CLI)

---

## ▶️ Como Executar

### Pré-requisitos:

* Java JDK instalado (versão 17 ou superior)

### Passos:

```bash
# Clone o repositório
git clone https://github.com/KaykeS8/chess-system-java.git

# Acesse a pasta
cd chesssystem

# Compile o projeto
javac application/Program.java

# Execute o programa
java application.Program
```

---

## 🎮 Como Jogar

* O jogo é executado no terminal
* Os jogadores inserem as posições no formato:

```
e2
e4
```

* O sistema valida automaticamente as jogadas

---

## 🚀 Melhorias Futuras

* Interface gráfica (JavaFX ou Web)
* Suporte a multiplayer online
* Sistema de ranking
* Histórico de partidas
* IA para jogar contra o computador

---

## 📌 Aprendizados

Durante o desenvolvimento deste projeto, foram aprimoradas habilidades como:

* Aplicação prática de OOP
* Organização e separação de responsabilidades
* Pensamento orientado a domínio

---

## 👨‍💻 Autor

**Kayke Simão**
Desenvolvedor Back-end Java

