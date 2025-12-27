<div align="center">
  <img width="500" height="137" alt="Image" src="https://github.com/user-attachments/assets/9203cfa7-140c-45ea-bd53-217bdd1bd230" />
</div>

# 🤸‍♂️ Projeto: Pontuação dos Atletas

Este projeto foi desenvolvido como parte do desafio de certificação de lógica de programação. O objetivo é criar uma aplicação em **JavaScript** capaz de calcular a média de notas de atletas em uma competição de ginástica artística.

## 📋 Regras de Negócio

Para garantir uma avaliação justa, a competição segue as seguintes regras:
1.  Cada jurado avalia o atleta com notas de 1 a 10.
2.  São recebidas **5 notas** por atleta.
3.  O sistema deve **eliminar a maior e a menor nota**.
4.  A média final é calculada com base apenas nas **3 notas restantes**.

## 🚀 Tecnologias Utilizadas

* JavaScript

## 💻 Como Funciona o Código

O algoritmo segue os seguintes passos para cada atleta:
1.  **Ordena** as notas em ordem crescente (`sort`).
2.  **Remove** a primeira (menor) e a última (maior) nota (`slice`).
3.  **Soma** as notas válidas restantes (`forEach` ou `reduce`).
4.  **Calcula** a média dividindo pelo número de notas computadas (`length`).
5.  **Exibe** o resultado formatado no console.

## 📂 Estrutura de Dados (Entrada)

O sistema recebe uma matriz de objetos seguindo este modelo:

```javascript
let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas:  [8, 10, 10, 7, 9.33]
 }
];
```

## 🏃‍♂️ Como Executar

Você pode rodar este projeto de duas formas:

### 1. Pelo Terminal (Node.js)
Certifique-se de ter o Node.js instalado e execute:

```bash
node notas-atletas.js
```

### 2. Pelo Navegador
1. Copie o código do arquivo `notas-atletas.js`.
2. Abra o console do seu navegador (F12).
3. Cole o código e aperte **Enter**.

---
Desenvolvido por **[Albertina Rodrigues]** 🚀
