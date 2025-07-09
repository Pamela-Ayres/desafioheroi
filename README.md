# Desafio - Escrevendo as Classes de um Jogo

Este projeto contém uma implementação simples em JavaScript de uma classe `Heroi`, projetada para demonstrar conceitos básicos de Programação Orientada a Objetos (POO), como classes, construtores, propriedades e métodos.

## 📖 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [⚙️ Funcionalidades](#️-funcionalidades)
- [🚀 Como Usar](#-como-usar)


---

## 📝 Sobre o Projeto

O objetivo principal é criar uma estrutura básica para representar diferentes tipos de heróis em um jogo. A classe `Heroi` permite instanciar objetos com características específicas (nome, idade e tipo) e define um comportamento padrão (o método `atacar`).

A lógica do ataque é determinada pelo tipo do herói, resultando em uma mensagem personalizada que é exibida no console.

---

## ⚙️ Funcionalidades

- **Criação de Heróis**: A classe `Heroi` é instanciada com três parâmetros:
  - `nome`: O nome do herói (String).
  - `idade`: A idade do herói (Number).
  - `tipo`: O tipo do herói (String), como "mago", "guerreiro", etc. O tipo é automaticamente convertido para minúsculas para garantir a consistência.

- **Ataque Personalizado**: O método `atacar()` gera uma mensagem de ataque baseada no `tipo` do herói:
  - **Mago**: ataca usando `magia`.
  - **Guerreiro**: ataca usando `espada`.
  - **Monge**: ataca usando `artes marciais`.
  - **Ninja**: ataca usando `shuriken`.
  - **Outros Tipos**: Se um tipo não reconhecido for usado, ele usará um `ataque desconhecido`.

- **Saída no Console**: O resultado da ação de ataque é impresso diretamente no console, informando qual herói atacou e qual arma ou técnica foi utilizada.

---

## 🚀 Como Usar

### Pré-requisitos

Para executar este código, você precisa de um ambiente que execute JavaScript, como:
- [Node.js](https://nodejs.org/) instalado em sua máquina.
- O console de um navegador web.
