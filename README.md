# 🍔 DevBurger – Protótipo de Cardápio Digital

Bem-vindo(a) ao **DevBurger**, o protótipo de um cardápio digital para a nova hamburgueria gourmet!  
Este projeto foi desenvolvido como desafio para praticar **Node.js** e **Express**, explorando conceitos fundamentais de **rotas**, **requisições HTTP** e **servidores web**.

---

## 🎯 **Visão Geral do Projeto**

O objetivo é criar uma aplicação web simples e funcional, exibindo o cardápio da hamburgueria e permitindo que os clientes enviem sugestões de novos lanches.  
Nesta primeira fase, **não utilizamos banco de dados** – todos os dados e exibições são tratados diretamente pelo servidor.

---

## 📂 **Estrutura de Arquivos**

```bash
devburger/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │    └── logo.png (opcional)
│   ├── data/
│   │    └── lanches.json
│   └── 404.html (opcional)
│
├── views/
│   ├── index.html
│   └── contato.html        
│
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── server.js
```

## 🚀 Como Iniciar o Servidor
Clone o repositório e inicialize o package.json:
```
npm init -y
```

Instale as dependências:
```
npm install express
```

## 🔗 **Rotas Implementadas**

| Rota            | Método | Descrição                                                                 |
|-----------------|--------|---------------------------------------------------------------------------|
| `/`             | GET    | Página principal (index.html) com cardápio e formulário de sugestões.      |
| `/sugestao`     | GET    | Exibe mensagem de agradecimento com dados enviados via query string.       |
| `/contato`      | GET    | Exibe o formulário de contato (contato.html).                              |
| `/contato`      | POST   | Recebe dados do formulário e exibe página de contato recebido.             |
| `/api/lanches`  | GET    | Retorna lista de lanches em formato JSON.                                  |
| `*`             | ALL    | Página 404 personalizada para rotas não existentes.                        |

---

## 📚 Aprendizados

Criação de rotas GET e POST com Express.

Envio e recebimento de dados via query string e body (POST).

Organização de arquivos estáticos e páginas HTML com views e public.

Criação de uma API simulada retornando JSON.

Implementação de página personalizada para erros 404.

---

## 🙌 Agradecimentos

Este projeto faz parte da **Etapa 1 do Journey Backend - WebTech**, sendo apenas o início da minha evolução no Backend.  
Estou aberto(a) a sugestões de melhorias, novas ideias e feedbacks que possam levar esta aplicação para um próximo nível.  

Obrigado por conferir este projeto! 🚀  

