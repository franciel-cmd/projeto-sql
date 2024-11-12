# Levantamento de Requisitos

**Entrevista com Stakeholder e Evidenciação das Informações Obtidas.**

**Aluno**: Franciel Marques Fagundes  
**Disciplina**: Database Modeling & SQL

---

### 1. Quais informações devem ser armazenadas sobre os clientes?
**Resposta**: Nome completo, CPF, endereço, telefone, e-mail, histórico de compras, e a data de cadastro no sistema.

### 2. Quais dados são necessários sobre os produtos vendidos?
**Resposta**: Nome do produto, valor de compra, valor de venda, categoria, descrição, código de barras, preço, quantidade em estoque, data de validade (quando aplicável) e o fornecedor de cada produto.

### 3. Quais informações dos colaboradores devem ser armazenadas?
**Resposta**: Nome completo, CPF, cargo, salário, telefone, e-mail, departamento, número de registro e a data de contratação.

### 4. Quais dados dos fornecedores são necessários?
**Resposta**: Nome do fornecedor, CNPJ, telefone, e-mail, endereço, valor do frete e lista de produtos fornecidos.

### 5. Que informações são essenciais para registrar uma venda?
**Resposta**: Data e hora da venda, cliente que realizou a compra, colaborador que processou a venda, valor total, método de pagamento, possíveis descontos e o status da venda.

### 6. Como devemos armazenar os itens de cada venda?
**Resposta**: ID da venda, ID de cada produto, quantidade comprada de cada item, preço unitário de cada produto e o subtotal para cada item da venda.

### 7. Que informações devem ser registradas no controle de estoque?
**Resposta**: Quantidade disponível de cada produto, localização do produto no depósito, e as datas de entrada e saída de mercadorias.

### 8. Quais informações devemos armazenar sobre os pedidos de compra feitos aos fornecedores?
**Resposta**: Fornecedor responsável, número do pedido, data do pedido, data prevista de entrega, valor total do pedido e o status do pedido.

### 9. Que informações são necessárias armazenar para os pagamentos das vendas?
**Resposta**: Método de pagamento, data do pagamento, valor pago, status do pagamento e a associação do pagamento à venda correspondente.

### 10. Como devemos registrar as devoluções feitas pelos clientes?
**Resposta**: ID da venda original, cliente que fez a devolução, produto devolvido, quantidade devolvida, valor devolvido ao cliente, data da devolução, motivo da devolução e o status da devolução.
