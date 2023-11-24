# OpenAI Project

Welcome to the OpenAI project! This repository combines both Front-End and Back-End components to provide a seamless experience for generating and managing images based on user-provided text.

## Server Dependencies

The server utilizes the following dependencies:

- **cloudinary** v1.34.0
- **cors** v2.8.5
- **dotenv** v16.0.3
- **express** v4.18.2
- **mongoose** v6.10.0
- **nodemon** v2.0.20
- **openai** v3.1.0

## Front-End Dependencies

The Front-End relies on the following dependencies:

### Dependencies
- **file-saver** v2.0.5
- **react** v18.2.0
- **react-dom** v18.2.0
- **react-router-dom** v6.8.1

### DevDependencies
- **@types/react** v18.0.27
- **@types/react-dom** v18.0.10
- **@vitejs/plugin-react** v3.1.0
- **autoprefixer** v10.4.13
- **gh-pages** v5.0.0
- **postcss** v8.4.21
- **tailwindcss** v3.2.6
- **vite** v4.1.0

## Server Details

The server is built with Express and uses MongoDB as its database. It leverages the OpenAI API to generate images based on user-provided text, which are then stored in MongoDB. The server is hosted on Render.

⚠️ **Disclaimer:** Due to the free hosting nature, the server may experience downtime when not in use, resulting in delayed access.

## Web Interface

Upon accessing the website, users can view previously generated images along with the contributor's name. The search functionality allows users to filter images based on their preferences. Clicking the "Create" button triggers a request to the OpenAI API, followed by the generation and posting of the image on the server.

---

# Projeto OpenAI

Bem-vindo ao projeto OpenAI! Este repositório combina componentes de Front-End e Back-End para proporcionar uma experiência integrada na geração e gerenciamento de imagens com base no texto fornecido pelo usuário.

## Dependências do Servidor

O servidor utiliza as seguintes dependências:

- **cloudinary** v1.34.0
- **cors** v2.8.5
- **dotenv** v16.0.3
- **express** v4.18.2
- **mongoose** v6.10.0
- **nodemon** v2.0.20
- **openai** v3.1.0

## Dependências do Front-End

O Front-End depende dos seguintes pacotes:

### Dependências
- **file-saver** v2.0.5
- **react** v18.2.0
- **react-dom** v18.2.0
- **react-router-dom** v6.8.1

### DevDependencies
- **@types/react** v18.0.27
- **@types/react-dom** v18.0.10
- **@vitejs/plugin-react** v3.1.0
- **autoprefixer** v10.4.13
- **gh-pages** v5.0.0
- **postcss** v8.4.21
- **tailwindcss** v3.2.6
- **vite** v4.1.0

## Detalhes do Servidor

O servidor é construído com Express e utiliza o MongoDB como banco de dados. Ele faz uso da API da OpenAI para gerar imagens com base no texto fornecido pelo usuário, que são então armazenadas no MongoDB. O servidor está hospedado na plataforma Render.

⚠️ **Aviso:** Devido à natureza gratuita da hospedagem, o servidor pode ficar inativo quando não está em uso, resultando em acesso mais demorado.

## Interface Web

Ao acessar o site, os usuários podem visualizar imagens geradas anteriormente, juntamente com o nome do contribuidor. A funcionalidade de busca permite aos usuários filtrar imagens de acordo com suas preferências. Ao clicar no botão "Criar", é acionada uma requisição à API da OpenAI, seguida pela geração e postagem da imagem no servidor.

