# Jogoteca
O Jogoteca é um projeto desenvolvido em Python em conjunto com outras tecnologias como HTML e CSS (com o Bootstrap para estilizar a página) para aplicar e consolidar conhecimentos básicos do desenvolvimento web, utilizando o Flask. Sendo a Jogoteca, um catálogo de jogos que permitem a visualização e gestão de uma lista de títulos.

🎮 Projeto Jogoteca: Catálogo de Jogos em Flask

Este projeto é uma aplicação web simples desenvolvida em Python utilizando o framework Flask. O principal objetivo foi aplicar e consolidar conhecimentos básicos de desenvolvimento web com Flask, criando um catálogo de jogos que permite a visualização e gestão de uma lista de títulos.

## 🌟 Destaques do Projeto

Estrutura Flask: Aplicação completa e funcional construída do zero com o micro-framework Flask.

Design Frontend: Interface de usuário elegante e responsiva, desenvolvida com HTML e Bootstrap.

Autenticação: Implementação de um sistema básico de login e autorização para proteger rotas.

Roteamento Eficiente: Definição de rotas, uso de templates (Jinja2) e aplicação de redirecionamentos para gerenciar o fluxo da aplicação.

URLs Dinâmicas: Criação de URLs que aceitam parâmetros variáveis, como para visualizar ou editar um jogo específico.

## 🌟 Funcionalidades e Conhecimentos Aplicados

O desenvolvimento do Jogoteca focou em atingir os seguintes objetivos de aprendizado do curso de Flask:

- Criação de Aplicação Web com Flask: Estruturação de uma aplicação web completa, desde a inicialização do app até a configuração básica.

- Design Responsivo com Frontend: Implementação de um site com layout elegante, utilizando HTML e Bootstrap para garantir um design moderno e responsivo.

- Sistema de Autenticação: Desenvolvimento de um sistema básico de login e autorização, permitindo acesso a certas funcionalidades apenas para usuários autenticados.

- Rotas, Templates e Redirecionamentos:

  - Definição de rotas (@app.route) para mapear URLs a funções.

  - Utilização de templates (Jinja2) para renderizar o conteúdo dinâmico.

  - Aplicação de redirecionamentos (redirect) para guiar o fluxo do usuário (ex: após login/logout).

  - URLs Dinâmicas: Criação de URLs que aceitam parâmetros variáveis para exibir detalhes ou manipular recursos específicos (ex: /editar/<id_do_jogo>).

## ⚙️ Como Executar

Para rodar este projeto localmente, siga os passos abaixo:

### Clone o repositório:
    
    git clone [LINK_DO_SEU_REPOSITÓRIO]
    cd jogoteca

### Crie e ative um ambiente virtual (recomendado):

    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    venv\Scripts\activate  # Windows

### Instale as dependências:

    pip install -r requirements.txt  # Assumindo que você tem um requirements.txt com Flask, etc.

Ou instale Flask diretamente:
    
    pip install Flask

### Execute a aplicação:

    python [NOME_DO_SEU_ARQUIVO_PRINCIPAL].py (no meu caso jogoteca.py)

Acesse no navegador: Abra seu navegador e acesse a URL: http://127.0.0.1:5000
