# EcommerceStore
# Loja Virtual com .NET 8 e React

## **Descrição do Desafio**
O desafio consiste em desenvolver uma loja virtual básica que permita aos usuários:

- Visualizar produtos disponíveis na loja.
- Pesquisar produtos por nome ou categoria.
- Adicionar produtos ao carrinho de compras.
- Atualizar quantidades ou remover produtos do carrinho.
- Finalizar a compra, integrando com uma API de pagamento como a Pagar.me.
- Autenticar usuários, permitindo login, registro e acesso ao histórico de compras.

A aplicação deve ser responsiva, permitindo uma experiência fluida tanto em dispositivos móveis quanto em desktops.

## **Funcionalidades da Loja Virtual**
1. **Página Inicial (Homepage):**
   - Exibição de produtos em destaque.
   - Barra de pesquisa para encontrar produtos por nome ou categoria.

2. **Listagem de Produtos (Product Listing):**
   - Exibição de todos os produtos disponíveis, com opções para ordenar por preço ou popularidade.

3. **Detalhes do Produto (Product Details):**
   - Visualização de informações detalhadas do produto.
   - Botão para adicionar ao carrinho de compras.

4. **Carrinho de Compras (Shopping Cart):**
   - Exibição dos produtos adicionados ao carrinho, com possibilidade de atualizar quantidades ou remover itens.
   - Cálculo automático do preço total.

5. **Finalização da Compra (Checkout):**
   - Coleta de informações do usuário, como endereço de entrega e dados de pagamento.
   - Validação dos dados antes de processar o pedido.

6. **Confirmação de Pedido (Order Confirmation):**
   - Exibição de um resumo do pedido, incluindo detalhes dos produtos comprados, valor total e status da entrega.

7. **Autenticação de Usuário (User Authentication):**
   - Registro e login de usuários para acessar informações personalizadas e histórico de compras.

## **Tecnologias Utilizadas**

### **Backend: .NET 8**
- **ASP.NET Core**:
  - Utilizado para desenvolver a API RESTful, gerenciando requisições e respostas entre o front-end e o banco de dados.

- **Entity Framework Core**:
  - Gerenciador ORM para interagir com o banco de dados, permitindo operações de CRUD com as entidades da aplicação.

- **Autenticação JWT**:
  - Implementação de autenticação segura para registro e login de usuários.

- **API de Pagamento (Pagar.me)**:
  - Integração para processar pagamentos de maneira segura e confiável.

### **Frontend: React**
- **React com TypeScript**:
  - Framework JavaScript utilizado para criar a interface do usuário de forma dinâmica e reativa.

- **Material-UI ou Tailwind CSS**:
  - Biblioteca de componentes e framework CSS para criar uma interface moderna e responsiva.

- **React Context API ou Redux**:
  - Gerenciamento de estado global para controlar o carrinho de compras e a autenticação do usuário.

### **Banco de Dados**
- **SQL Server**:
  - Armazena as informações dos produtos, usuários, carrinho e pedidos.

### **Testes e Documentação**
- **Swagger**:
  - Ferramenta para documentar e testar os endpoints da API.

- **Postman**:
  - Ferramenta utilizada para validar as requisições da API durante o desenvolvimento.

### **Controle de Versão**
- **Git e GitHub**:
  - Versionamento do código e colaboração no repositório.

---

Com essa combinação de tecnologias, o sistema será escalável, robusto e seguro, oferecendo uma experiência de usuário de alta qualidade. Se você tiver dúvidas ou quiser mais detalhes sobre o desenvolvimento, fique à vontade para perguntar!

