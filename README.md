<div align="center">

# 🎯 Jogo do Número Secreto

**Descubra o número sorteado entre 1 e 100 com a ajuda de dicas e narração por voz.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Speech API](https://img.shields.io/badge/Web_Speech_API-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

</div>

---

## 📑 Índice

- [Sobre o projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Como jogar](#%EF%B8%8F-como-jogar)
- [Como executar](#-como-executar)
- [Estrutura do projeto](#-estrutura-do-projeto)
- [Tecnologias](#%EF%B8%8F-tecnologias)
- [Créditos](#-créditos)

---

## 📋 Sobre o projeto

Um jogo de adivinhação em que o usuário precisa descobrir um número secreto sorteado entre **1 e 100**. A cada palpite, o jogo informa se o número secreto é **maior** ou **menor** que o valor digitado. As mensagens exibidas na tela também são **narradas por voz**, usando a Web Speech API.

Este projeto foi desenvolvido com base nos cursos da **Alura**. A **lógica em JavaScript foi implementada por mim**, enquanto o **HTML e o CSS** (estrutura e estilo visual) foram fornecidos pelo curso.

## ✨ Funcionalidades

- 🎲 **Sorteio aleatório** de um número entre 1 e 100, sem repetição até que todos os números tenham sido sorteados
- 💡 **Dicas inteligentes** de "maior" ou "menor" a cada palpite
- 🔢 **Contador de tentativas** até o acerto
- 🔊 **Narração por voz** das mensagens exibidas na tela (Web Speech API)
- 🔄 **Botão de reinício** para começar uma nova partida com outro número secreto
- 📱 **Layout responsivo**

## 🕹️ Como jogar

1. Digite um número entre **1 e 100** no campo de entrada
2. Clique no botão **"Chutar"**
3. Siga as dicas exibidas na tela (*"O número secreto é maior/menor"*) até acertar
4. Ao acertar, o botão **"Novo jogo"** será habilitado para reiniciar a partida

## 🚀 Como executar

Não é necessário servidor nem instalação de dependências — o projeto é 100% front-end.

```bash
# 1. Clone o repositório
git clone <url-do-repositorio>

# 2. Entre na pasta do projeto
cd <nome-da-pasta>
```

Em seguida, abra o arquivo `index.html` no navegador de sua preferência.

## 📁 Estrutura do projeto

```text
├── index.html    # Estrutura da página
├── style.css     # Estilização visual
├── app.js        # Lógica do jogo (desenvolvida por mim)
└── img/          # Imagens utilizadas no layout
```

## 🛠️ Tecnologias

| Tecnologia | Uso no projeto |
| --- | --- |
| **HTML5** | Estrutura da página |
| **CSS3** | Estilização e responsividade |
| **JavaScript (Vanilla)** | Lógica do jogo e manipulação do DOM |
| **Web Speech API** | Síntese de voz para narrar as mensagens |

## 📚 Créditos

Projeto baseado nos cursos da [Alura](https://www.alura.com.br/) de **Lógica de Programação** e **Git e GitHub**.

---

<div align="center">

Feito com 💜 por [Seu Nome](https://github.com/seu-usuario)

</div>