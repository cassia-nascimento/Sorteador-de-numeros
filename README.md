<h1 align="center">
  🎲 Sorteador de Números
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Alura-ONE-Orange?style=for-the-badge" alt="Alura ONE">
</p>

Projeto prático desenvolvido durante o curso **"JavaScript: explorando funções e listas"**, integrante da trilha de Front-End do programa **Oracle Next Education (ONE)** em parceria com a **Alura**.

A aplicação consiste em um gerador de números aleatórios customizável, onde o usuário determina a quantidade de números a serem sorteados, além do intervalo inicial (valor mínimo) e final (valor máximo).

---

## 📌 Funcionalidades e Regras de Negócio

O motor lógico do sistema (implementado puramente em `app.js`) gerencia os estados da interface e valida os dados de entrada com base nas seguintes diretrizes:

* **Sorteio Único (Sem Repetição):** Através de estruturas de repetição (`while`) e arrays de controle, o sistema garante que um mesmo número não seja sorteado mais de uma vez na mesma rodada.
* **Manipulação Dinâmica de Estados (DOM):** O botão *Reiniciar* altera suas classes CSS em tempo real (`container__botao-desabilitado` vs `container__botao`), tornando-se clicável apenas após a exibição de um resultado válido.
* **Prevenção de Loops Infinitos:** O código conta com uma validação lógica inteligente: se a quantidade de números solicitada for maior do que o intervalo disponível entre o valor mínimo e máximo, o sistema emite um alerta para evitar travamento de memória do navegador.

---

## 📂 Estrutura do Repositório

```text
sorteador-de-numeros
├── img/                # Assets visuais e ícones de suporte da interface
├── app.js              # Camada lógica (algoritmo de sorteio e manipulação de DOM)
├── index.html          # Estrutura semântica da aplicação
└── style.css           # Estilização estática e tokens visuais

```

---

## 🚀 Como Executar o Projeto

Por se tratar de uma aplicação client-side pura, você não precisa instalar servidores backend.

1. Clone o repositório em sua máquina:
```bash
git clone [https://github.com/cassia-nascimento/sorteador-de-numeros.git](https://github.com/cassia-nascimento/sorteador-de-numeros.git)

```


2. Acesse a pasta do projeto:
```bash
cd sorteador-de-numeros

```


3. Abra o arquivo `index.html` diretamente em qualquer navegador web (Chrome, Firefox, Edge, Safari).

---

## 👩‍💻 Autora

Projeto de capacitação técnica desenvolvido por **Cássia Nascimento**.

* [GitHub Profile](https://github.com/cassia-nascimento)
* [LinkedIn](https://www.linkedin.com/in/cassia--nascimento/)
