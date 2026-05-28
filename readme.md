# 🧠 SysAgent | Mentor Neuropedagógico e Gestor de Rotina

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Em%20Produção-success?style=for-the-badge)

> Uma Single Page Application (SPA) desenvolvida para otimizar o desempenho cognitivo, gerindo cronogramas de estudo de alta complexidade para profissionais em escalas de trabalho exigentes (ex: 12x36).

## 🎯 O Problema e a Solução

Conciliar uma escala de trabalho exaustiva com os rigores de uma licenciatura em Ciência da Computação exige mais do que motivação; exige um sistema. 
O **SysAgent** foi concebido para resolver o problema da fadiga de decisão e do esgotamento cognitivo. Baseado em metodologias neuropedagógicas (como a *Prática Intercalada* e a *Evocação Ativa*), o sistema automatiza o planeamento, gere ciclos de foco e centraliza recursos (PDFs e vídeos) para disciplinas críticas como Arquitetura de Computadores, Engenharia Reversa e Criptografia.

## ✨ Funcionalidades Principais (Features)

- **Matriz de Execução Dinâmica:** Renderização de cronogramas diários injetados via DOM de forma assíncrona, adaptados à escala do utilizador.
- **Motor Pomodoro Integrado (50/10):** Temporizador de precisão que gere os ciclos de foco profundo e pausas estratégicas.
- **Persistência de Dados (Local Storage):** Registo contínuo da carga cognitiva acumulada do utilizador. Os dados sobrevivem a atualizações e encerramentos do ecrã do navegador.
- **Integração com API Externa (Fetch API):** Consumo assíncrono (Promises/Async-Await) de uma REST API pública para fornecer mensagens e "pílulas" de raciocínio.
- **Acessibilidade e Semântica Nativa:** Utilização intensiva de APIs HTML5 (como `<dialog>` e `<details>`) para modais nativos e menus sanfonados, reduzindo o peso do JavaScript e melhorando a acessibilidade para leitores de ecrã.

## 🛠️ Arquitetura e Stack Tecnológica

O projeto foi construído sob a premissa de *Clean Code* e *Zero Dependencies*, utilizando exclusivamente tecnologias web nativas:

* **HTML5 Semântico:** Estruturação clara com `<aside>`, `<main>`, `<article>`, melhorando o SEO e a acessibilidade.
* **CSS Moderno:** * Layout responsivo recorrendo a `CSS Grid` e `Flexbox`.
  * *Design System* centralizado através de Variáveis CSS (`:root`).
  * Animações de interface (loaders e transições de estado) utilizando `@keyframes` puramente em CSS, aliviando a *main thread* do JavaScript.
* **JavaScript (Vanilla JS):** Lógica de estado e manipulação do DOM sem recurso a *frameworks* externas. 

## 🚀 Como Executar o Projeto

Sendo uma aplicação estática *client-side*, a execução é imediata e não requer a instalação de módulos ou servidores Node.js.

1. Faça o clone do repositório:
   ```bash
   git clone [https://github.com/WagnerxOliveira/SysAgent.git](https://github.com/wagnerxoliveira/SysAgent.git)