# 🧑‍💻 Projeto Social Uzumaki

**Educar para transformar vidas e construir futuros.**

Este é o código-fonte do website institucional para o Projeto Social Uzumaki, com foco em acessibilidade (WCAG 2.1 Nível AA) e boas práticas de desenvolvimento.

## 🌟 Funcionalidades

* **Páginas Institucionais:** Início, Projetos e Cadastro.
* **Formulário de Cadastro:** Validação e máscaras (CPF, Telefone, CEP) via JavaScript.
* **Navegação Acessível:** Estrutura semântica HTML e suporte a navegação por teclado.
* **Modo Escuro Acessível:** Implementação de tema escuro via `prefers-color-scheme`.

## ♿ Acessibilidade (WCAG 2.1 Nível AA)

O projeto foi desenvolvido seguindo as diretrizes WCAG 2.1 Nível AA, garantindo:

1.  **Estrutura Semântica:** Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` e associações `<label for="...">` corretas.
2.  **Contraste:** Garantia de contraste de cores mínimo de 4.5:1 para texto normal.
3.  **Foco:** Suporte completo à navegação por teclado (visível *outline* nos elementos interativos).
4.  **Leitores de Tela:** Suporte a leitores de tela e padronização de títulos e nomes.

## 🚀 Como Executar Localmente

1.  **Clone o Repositório:**
    ```bash
    git clone (https://oferbs01.github.io/Projeto_Social_Uzumaki/)
    ```
2.  **Abra os Arquivos:**
    Abra `index.html` no seu navegador. O site é totalmente estático e não requer servidor.

## 🌲 Estratégia de Branching (GitFlow)

Adotamos o modelo GitFlow, que separa o trabalho em branches dedicadas:

* `main`: Versão estável e em produção.
* `develop`: Versão de desenvolvimento mais recente.
* `feature/*`: Novas funcionalidades.
* `release/*`: Preparação para novas versões.
* `hotfix/*`: Correções urgentes na produção.
