# Guanxi

**Guanxi IA** é uma solução de inteligência artificial desenvolvida para automatizar o atendimento ao cliente de pequenos e médios empreendedores. Nossa ferramenta permite que você ofereça um atendimento eficiente, personalizado e escalável, melhorando a experiência do cliente e otimizando as operações do seu negócio.

## Índice

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Começando](#começando)
    - [Pré-requisitos](#pré-requisitos)
    - [Instalação](#instalação)
    - [Configuração](#configuração)
- [Uso](#uso)
- [Contribuindo](#contribuindo)
- [Testes](#testes)
- [Deploy](#deploy)
- [Licença](#licença)
- [Contato](#contato)
- [Agradecimentos](#agradecimentos)

## Tecnologias Utilizadas

- **Python**
- **Django**
- **DRF**
- **Typescript**
- **Nextjs**

## Começando

### Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- **Git:** Versão 2.20 ou superior
- **Node.js:** Versão 18.x ou superior
- **npm:** Versão compatível com node.js
- **Python:** Versão 3.8 ou superior

### Instalação

1. **Clone o Repositório**

    ```bash
    git clone https://github.com/Tiagohbello/guanxi-back.git
    cd guanxi-back
    ```

2. **Instale as Dependências**

   ### Frontend

    ```bash
    npm install
    ```

   ### Backend

   #### Node.js

    ```bash
    npm install
    ```

   #### Python

    ```bash
    pip install -r requirements.txt
    ```

3. **Configuração das Variáveis de Ambiente**

   Crie um arquivo `.env` na raiz do projeto.

   Abra o arquivo `.env` e preencha os valores conforme necessário:

    ```env
    # Exemplo de variáveis de ambiente
    DATABASE_URL=postgres://usuario:senha@localhost:5432/nome_do_banco
    API_KEY=suachaveapi
    SECRET_KEY=suachavesecreta
    ```

## Uso

### Executando o Projeto Localmente

#### Frontend

Para iniciar o servidor de desenvolvimento do frontend:

```bash
npm run dev
