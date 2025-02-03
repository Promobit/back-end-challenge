<img src="https://i.imgur.com/6q2AiRg.png" width="500">

# Introdução

Olá! Obrigado pelo interesse em participar do nosso processo seletivo para desenvolvedor backend no [Promobit](https://www.promobit.com.br/).


## 📌 Índice
- [Objetivo](#objetivo)
- [Desafio](#desafio)
- [Requisitos](#requisitos)
- [Seria bom se fizesse (Opcional)](#seria-bom-se-fizesse-opcional)
- [Techs (Obrigatório)](#techs-obrigatorio)
- [Como entregar](#como-entregar)
- [O que será avaliado](#o-que-sera-avaliado)
- [Orientações](#orientacoes)

---

## 🎯 Objetivo
O objetivo deste desafio é avaliar suas habilidades e conhecimento em desenvolvimento **Back-End**, utilizando **API Rest** para gerenciar produtos, categorias e tags.  

📌 _O foco principal da avaliação será a construção do **Back-End**. O **Front-End** é opcional, mas caso decida implementá-lo, ele **não deve ter dependências diretas** com o Back-End, sendo todas as operações realizadas via requisições HTTP._

---

## 🚀 Desafio
Construir uma API para gerenciamento de produtos, categorias e tags, inspirada no site do **Promobit**.  

A API deve permitir o **CRUD completo** para produtos e tags, além de gerenciar o relacionamento entre eles.  

---

# 📜 Requisitos  

Recursos necessários: Produtos, Tags, Categorias e Relacionamento entre eles.  

- Baseado no site do Promobit, construir uma API de produtos, categorias e tags.  
- Documentação da API: Deve conter uma explicação clara de como consumir os endpoints, podendo ser via OpenAPI, Postman Collection ou README.md.  
- Endpoints:  

## 🛒 Produtos  
- **Criação de produtos**:  
  - Deve permitir criar produtos com nome, descrição e preço.  
  - Deve permitir vincular uma ou mais **tags** ao produto.  
  - Deve permitir vincular uma **categoria** ao produto.  
  - O nome do produto deve ser único na base.  
  - Não deve ser permitido salvar produto sem categorização.  
- **Listagem de produtos com ordenação** por:  
  - Nome  
  - Preço  
  - Curtidas  
- **Edição de produtos**:  
  - Deve permitir editar o nome, descrição e preço do produto.  
  - Deve permitir vincular uma ou mais **tags** ao produto.  
  - Deve permitir vincular uma **categoria** ao produto.  
  - O nome do produto deve ser único na base.  
  - Não deve ser permitido salvar produto sem categorização.  
- **Remoção de produtos**:  
  - Deve permitir remover um produto.  

## 🏷 Tags  
- **Criação de tags**:  
  - Deve permitir criar tags com nome.  
  - O nome da tag deve ser único na base.  
- **Listagem de tags** com:  
  - Nome  
- **Edição de tags**:  
  - Deve permitir editar o nome da tag.  
- **Remoção de tags**:  
  - Deve permitir remover uma tag.  
- **Vínculo de tags a produtos**:  
  - Deve permitir vincular uma ou mais **tags** a um produto.  
- **Listagem de tags de um produto** com:  
  - Nome  

## 📂 Categorias  
- **Criação de categorias**:  
  - Deve permitir criar categorias com nome.  
  - O nome da categoria deve ser único na base.  
- **Listagem de categorias** com:  
  - Nome  
- **Edição de categorias**:  
  - Deve permitir editar o nome da categoria.  
- **Remoção de categorias**:  
  - Deve permitir remover uma categoria **somente se não houver produtos vinculados a ela**.  
- **Vínculo de categorias a produtos**:  
  - Um produto deve ter **exatamente uma categoria** vinculada.  
  - A alteração de categoria de um produto deve ser permitida.  
- **Listagem de produtos por categoria**:  
  - Deve permitir listar todos os produtos de uma categoria específica.  

---
## 📝 Observações

- O projeto **não precisa de upload de imagens**.
- **Não é necessário vincular produtos a usuários**.

💡 **Caso opte por desenvolver um Front-End, fique à vontade para usar qualquer framework, mas lembre-se de que o Back-End deve ser independente!**

---

## 🌟 Diferenciais (Opcional)
Se quiser ir além, aqui estão algumas sugestões que serão valorizadas:  

- 🔐 **Autenticação de usuário** (ex: JWT).  
- 🐳 **Docker + Docker Compose** para facilitar a execução do projeto.  
- 🌐 **Nível de maturidade de Richardson** (RESTful API).  
- 🧪 **Testes automatizados** (unitários e/ou de integração).    
- 🏗 **Uso de princípios SOLID** e boas práticas de design de software.  


---

## 🛠 Techs (Obrigatório)
- 🐘 **PHP 8+**
- 🛢 **Banco de dados relacional** de sua escolha (usamos MySQL, mas você pode usar outro)
- 🔧 Recomendamos fortemente que você desenvolva o Back-End **sem frameworks** ou utilize **Symfony**. Porém fique a vontade para utilizar outro framework se preferir.
- 📦 **Gerenciador de dependências Composer**.  

---

## 📤 Como entregar

1️⃣ **Suba seu código** num repositório privado no **GitHub** (Exemplo: `https://github.com/seu-nome/back-end-challenge.git`).  

2️⃣ **Envie o link do repositório** para o e-mail: [backend.engenharia@promobit.com.br](mailto:backend.engenharia@promobit.com.br) com o título: `[Backend Challenge] Seu Nome`.  

3️⃣ **Compartilhe o repositório** com o usuário `@promobit-backend-engenharia`.  

4️⃣ **Inclua um arquivo `README.md`** explicando como rodar o projeto localmente.

---

## 🏆 O que será avaliado
- ✅ **Organização do código e separação de responsabilidades**.  
- ✅ **Implementação de todos os requisitos obrigatórios**.  
- ✅ **Qualidade da documentação e facilidade de setup**.  
- ✅ **Boas práticas de desenvolvimento e segurança**.  

---

## 📌 Orientações
- ✨ Faça um código **claro, bem estruturado e sucinto**.  
- 🔗 **Coloque tudo em um repositório Git**.  
- 📄 **Documente bem o setup** no `README.md`.  
- 📥 **Seja consistente nos retornos de API** e use códigos HTTP apropriados.  
- 🛠 **Garanta que seja fácil rodar o projeto localmente**.  
- 💡 **Use sua criatividade e nos surpreenda!** 🎉  

---

🚀 **Boa sorte!** 🚀

