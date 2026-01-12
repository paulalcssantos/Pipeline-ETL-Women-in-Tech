# 🚀 Projeto Pipeline de ETL: Perfil da Mulher na Tecnologia

### Um Projeto-Guia para o Bootcamp WoMakersCode

Olá! Meu nome é **Paula Luiza**, e este repositório contém o projeto completo que desenvolvi e ministrei como instrutora no Bootcamp de BI da WoMakersCode.

Este projeto foi desenhado como um guia prático e realista, demonstrando a construção de um pipeline de dados do início ao fim. O objetivo é capacitar as alunas a responder perguntas relevantes sobre o perfil de mulheres na área de dados, utilizando um stack de ferramentas moderno, acessível e 100% gratuito.

---

## 🎯 Objetivo do Projeto (e do Módulo)

Este desafio foi estruturado para que as participantes aprendam a:
1.  **Extrair** dados de múltiplas fontes heterogêneas (CSV, SQL, API, JSON).
2.  **Carregar** esses dados brutos em um Data Warehouse central.
3.  **Transformar** e modelar os dados utilizando as melhores práticas de Engenharia Analítica.
4.  **Orquestrar** todo o processo para que ele seja executável de forma confiável e automatizada.
5.  **Visualizar** os insights gerados em um dashboard interativo.

---

## 🏛️ Arquitetura do Pipeline

O pipeline implementa uma arquitetura **ELT (Extract, Load, Transform)**, utilizando as seguintes ferramentas, escolhidas por sua relevância no mercado e acessibilidade:

*   **Ambiente de Desenvolvimento:** Google Colab
*   **Extração e Carga (EL):** Python, com as bibliotecas Pandas e Requests.
*   **Data Warehouse (DW):** SQLite
*   **Transformação (T):** dbt (Data Build Tool)
*   **Orquestração:** Prefect
*   **Visualização (BI):** Tableau Public

---

## 📊 Fontes de Dados

O pipeline integra quatro fontes de dados distintas para criar uma visão 360°:

| Fonte | Tipo | Ferramenta de Extração | Propósito no Projeto |
| :--- | :--- | :--- | :--- |
| **Kaggle Survey 2022** | CSV | Python + Pandas | Fornecer o panorama global sobre o perfil demográfico, técnico e salarial. |
| **Participantes do Bootcamp** | SQL (SQLite) | Python + Pandas | Simular dados internos para permitir a comparação do público do bootcamp com o cenário global. |
| **REST Countries API** | API (JSON) | Python + Requests | Enriquecer os dados geográficos, permitindo análises por região e continente. |
| **Categorias de Habilidades**| JSON | Python + json | Servir como um dicionário de metadados para categorizar e agrupar as habilidades técnicas. |

---

## 💻 Notebook do Projeto

O arquivo principal deste repositório é o notebook Jupyter que contém o código completo ensinado durante as aulas:

Este notebook guia as alunas por todas as etapas práticas, desde a configuração do ambiente até a definição do pipeline orquestrado com Prefect.

---

## ✨ Resultado Final: O Dashboard

O trabalho de engenharia de dados culmina em um dashboard interativo construído no Tableau Public. Ele permite explorar os dados e responder às perguntas que motivaram o projeto.

<img width="1853" height="836" alt="image" src="https://github.com/user-attachments/assets/47631762-d073-4ea7-bb54-28e61c9858bf" />

**[➡️ Clique aqui para ver o Dashboard Interativo no Tableau Public](https://public.tableau.com/app/profile/paula.luiza/viz/shared/5QSBSS89W)**

---

## 👩‍🏫 Sobre este Projeto e a Instrutora

Este repositório serve como o material de apoio oficial para as alunas do bootcamp, mas também como uma peça do meu portfólio, demonstrando a criação de um projeto de dados end-to-end com foco em didática e boas práticas de engenharia.

Eu sou **Paula Luiza**, Analista de Sistemas/Dados e Educadora, apaixonada por capacitar mais mulheres para a área de tecnologia. Desenvolvi e ministrei este módulo com o objetivo de fornecer uma experiência de aprendizado prática, relevante e inspiradora.

**Conecte-se comigo:**
*   **LinkedIn:** https://www.linkedin.com/in/paulalcssantos
