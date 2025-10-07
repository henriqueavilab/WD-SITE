# Vuelo - Sistema de Prospecção de Leads
## Projeto para a disciplina de Web Design - Engenharia da Computação (FACENS)

![Badge do Projeto](https://img.shields.io/badge/Projeto-FACENS%20Web%20Design-9370DB)

Este é um projeto desenvolvido para a disciplina de Web Design. Trata-se de uma aplicação web completa (front-end) para prospecção e gerenciamento de leads, chamada "Vuelo". O sistema permite que um usuário se cadastre, faça login e gerencie uma lista de estabelecimentos (leads), acompanhando o status e as etapas de contato de cada um.

*(Dica: Tire um print da tela do seu sistema e coloque aqui para deixar o README mais visual!)*
![Screenshot do Sistema Vuelo](https://i.imgur.com/8QfCjU1.png)

---

## ✨ Principais Funcionalidades

O sistema foi construído com foco na experiência do usuário e na funcionalidade, incluindo:

* **Autenticação de Usuários:**
    * Sistema completo de **Login** e **Cadastro**.
    * Os dados dos usuários são salvos de forma segura no `localStorage` do navegador para simular uma sessão.

* **Dashboard Interativo:**
    * **Visão Geral:** Cards que exibem estatísticas rápidas sobre a quantidade total de leads e sua distribuição entre status (Frios, Mornos, Quentes).
    * **Gráficos Dinâmicos:** Gráficos de pizza e rosca (utilizando Chart.js) que mostram a distribuição de leads por tipo de estabelecimento e por status, atualizados em tempo real.

* **Gerenciamento Completo de Leads:**
    * **Lista de Leads:** Tabela clara e organizada com todos os estabelecimentos.
    * **Ciclo de Status:** Altere o status de um lead (Sem Status → Frio → Morno → Quente) com um único clique.
    * **Acompanhamento de Contato:** Marque as etapas de contato (1º, 2º e 3º contato) para cada lead.

* **Filtros Avançados e Ordenação:**
    * Filtre a lista de leads por tipo de estabelecimento, bairro, status ou etapa de contato.
    * Ordene a lista por nome, tipo, bairro ou status para facilitar a visualização.

* **Busca e Detalhes:**
    * **Busca Rápida:** Um campo de busca permite encontrar estabelecimentos por nome, tipo, bairro ou endereço.
    * **Modal de Detalhes:** Clique para ver todas as informações de um lead, como nome, telefone, endereço e um campo para **adicionar e salvar observações**.

* **Persistência de Dados:**
    * Todas as alterações (status, etapas, observações) são salvas automaticamente no `localStorage`, garantindo que os dados não sejam perdidos ao recarregar a página.

* **Design Responsivo:**
    * A interface se adapta a diferentes tamanhos de tela, de desktops a dispositivos móveis.

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web modernas e focadas no front-end:

* **HTML5:** Para a estruturação semântica do conteúdo.
* **CSS3:** Para a estilização completa, utilizando conceitos modernos como Flexbox e Grid Layout para criar um layout responsivo e agradável.
* **JavaScript (ES6+):** Para toda a interatividade, manipulação do DOM, gerenciamento de dados e lógica da aplicação.

### Bibliotecas Externas:

* **Chart.js:** Para a criação dos gráficos interativos no dashboard.
* **Font Awesome:** Para os ícones utilizados na interface.
* **Google Fonts (Montserrat):** Para a tipografia do projeto.

---

## 🛠️ Como Executar o Projeto

Como este é um projeto puramente front-end, não é necessário um servidor ou ambiente de compilação.

1.  **Clone ou baixe este repositório:**
    ```bash
    git clone https://[URL-DO-SEU-REPOSITORIO].git
    ```
    Ou simplesmente baixe os arquivos `.zip`.

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd FACENS_WebDesign
    ```

3.  **Abra o arquivo `Index.html`:**
    * Clique duas vezes no arquivo `Index.html` no seu explorador de arquivos.
    * Ele será aberto diretamente no seu navegador padrão (Google Chrome, Firefox, etc.).

E pronto! O sistema estará funcionando. Você pode criar um novo usuário e começar a testar todas as funcionalidades.

---

## 📁 Estrutura dos Arquivos