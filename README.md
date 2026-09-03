# CadastramentoLoja

API REST para cadastro e gestão de produtos de loja, com upload de imagens integrado ao Cloudinary e suporte a dois bancos de dados (MongoDB e MySQL).

## Stack

- **Runtime:** Node.js
- **Framework:** Express 5
- **Banco de dados:** MongoDB (Mongoose) e MySQL (mysql2)
- **Upload de imagens:** Cloudinary + Multer

## Funcionalidades

- Cadastro, consulta e gestão de produtos
- Upload de imagens de produto direto para o Cloudinary
- CORS habilitado para consumo por um frontend separado

## Como rodar localmente

```bash
git clone https://github.com/EduardoAlkimim/CadastramentoLoja.git
cd CadastramentoLoja
npm install
```

Crie um arquivo `.env` (não versionado) com suas credenciais de banco e Cloudinary, depois:

```bash
npm start
```
