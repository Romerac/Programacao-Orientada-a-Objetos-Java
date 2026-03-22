# Exercício – Sistema de Notas de Aluno
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

# Descrição: 

Este repositório contém a resolução de um exercício prático de Programação Orientada a Objetos (POO) em Java. O objetivo é modelar uma classe para gerenciar as notas de um aluno e criar um menu interativo no console.

## 📝 Sobre o Exercício

A ideia aqui não é apenas criar uma classe simples, mas aplicar regras matemáticas específicas e criar uma interface interativa para quem estiver usando o programa. Os pontos principais desenvolvidos incluem:

* **Proteção de Dados (Encapsulamento):** As informações do aluno (como o RA e as notas) ficam privadas. A única forma de inserir ou ler esses dados é usando os métodos *getters* e *setters*. É como se o próprio objeto tomasse conta das suas informações.
* **A Classe faz o Trabalho Pesado:** A classe não serve só para guardar as notas. Os métodos de calcular as médias (`calcMediaProva`, `calcMediaTrab` e `calcMediaFinal`) mostram como o objeto pega os valores, aplica os cálculos com os pesos corretos e devolve o resultado pronto.
* **Um Menu que não Fecha:** Criação de um menu de opções utilizando a classe `Scanner`. O programa roda em um ciclo (usando comandos como `while` e `switch-case`) onde o usuário pode navegar entre as opções de visualização de notas até escolher a opção de "Sair". O RA do aluno é sempre exibido para lembrar qual registro estamos consultando.

## 🏗️ Estrutura da Classe

| `Aluno` |
| :--- |
| **Atributos** |
| `- RA : int` <br> *(Registro Acadêmico do Aluno)* |
| `- NtPrv1 : double` <br> *(Nota da primeira prova)* |
| `-
prjCirculo/
│
├── Aplic.java
└── Aluno.java
```

## Autores

- [@romerac](https://www.github.com/romerac)

