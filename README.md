# 🛡️ Projeto: Classificador de Nível de Herói

Este projeto simples em JavaScript tem como objetivo classificar um herói com base na sua experiência (XP). A partir da quantidade de XP informada, o programa define em qual nível o herói se encontra, seguindo uma lógica baseada em faixas de pontuação.

## 🚀 Tecnologias Utilizadas

- JavaScript (ES6)
- Node.js (opcional para testes locais no terminal)

## 📋 Descrição da Lógica

O programa recebe dois valores principais:

- `nome`: Nome do herói.
- `xp`: Pontuação de experiência.

Com base no valor de `xp`, o herói será classificado em um dos seguintes níveis:

| XP                   | Nível              |
|----------------------|--------------------|
| Menor que 1000       | Ferro              |
| 1001 - 2000          | Bronze             |
| 2001 - 5000          | Prata              |
| 6001 - 7000          | Ouro               |
| 7001 - 8000          | Platina Diamante   |
| 8001 - 9000          | Ascendente         |
| 9001 - 10000         | Imortal            |
| Maior que 10000      | Radiante           |
