# **Kruzer - Desafio Fullstack Pleno**

Desenvolver uma aplicação completa (front-end, back-end e banco de dados) utilizando ReactJS, Node.js e MongoDB. Além disso, o candidato deverá implementar testes unitários tanto para o front-end quanto para o back-end.

#### Descrição do Projeto
A aplicação será um sistema simples de gestão de catálogo de produtos, onde os usuários podem criar, ler, atualizar e excluir produtos e SKUs.

## **Requisitos do Projeto:**

### **Front-end - Utilizar ReactJS**

#### **1. Interface de Usuário:**
- Página principal com a lista de produtos.
- Formulário para adicionar um novo produto.
- Funcionalidade para editar um produto existente.
- Funcionalidade para excluir um produto.
- Página de detalhes do produto com a lista de SKUs associados.
- Formulário para adicionar um novo SKU.
- Funcionalidade para editar um SKU existente.
- Funcionalidade para excluir um SKU.

#### **2. Componentes**
- Componente ProductList para exibir a lista de produtos.
- Componente ProductForm para adicionar/editar produtos.
- Componente ProductItem para cada item da lista de produtos.
- Componente SkuList para exibir a lista de SKUs de um produto.
- Componente SkuForm para adicionar/editar SKUs.
- Componente SkuItem para cada item da lista de SKUs.

#### **3. Comunicação com o Back-End**
- Utilizar **react-query** para fazer requisições HTTP ao back-end.
- Gerênciar estado da aplicação utilizando useState, useEffect e useContext.

#### **4. Estilização**
- Utilizar uma biblioteca de componentes para React com suporte a tailwind para estilizar a aplicação.

### **Back-end - Utilizar NodeJS e KOA**

#### **1. API RESTful:**
- Endpoint para criar um novo produto: POST /api/products
- Endpoint para obter todos os produtos: GET /api/products
- Endpoint para obter um produto por ID: GET /api/products/:id
- Endpoint para atualizar um produto: PUT /api/products/:id
- Endpoint para excluir um produto: DELETE /api/products/:id
- Endpoint para criar um novo SKU: POST /api/products/:productId/skus
- Endpoint para obter todos os SKUs de um produto: GET /api/products/:productId/skus
- Endpoint para obter um SKU por ID: GET /api/skus/:id
- Endpoint para atualizar um SKU: PUT /api/skus/:id
- Endpoint para excluir um SKU: DELETE /api/skus/:id

#### **2. Validação e Segurança:**
- Validar dados de entrada (por exemplo, usando Joi ou Zod).
- Implementar CORS para permitir requisições do front-end.
- Tratar erros e retornar respostas apropriadas.

### **Banco de Dados - Utilizar MongoDB**

#### **1. Modelo de Dados:**
- Criar um modelo de produto com os seguintes campos: nome, código, descrição e imagem.
- Criar um modelo de SKU com os seguintes campos: código, EAN, descrição e uma referência ao produto.

### **Entregáveis**
- Código fonte da aplicação hospedado em um repositório público no GitHub.<br/>
- Instruções claras para rodar a aplicação localmente (de preferência no arquivo README).
- Ao finalizar, enviar e-mail para **felipe.martins@kruzer.io** com cópia para **andre.ciornavei@kruzer.io** e **eduardo.fernandes@kruzer.io**, notificando o término do desafio e com link para o repositório público.
- Esse desafio deve ser entregue em até 7 dias após a entrevista inicial.
  
---

Este desafio técnico oferece uma oportunidade para demonstrar habilidades sólidas no desenvolvimento de recursos para aplicações existentes, explorando a capacidade do candidato de interpretar pré-requisitos e entregar a demanda de acordo com as premissas estabelecidas.
