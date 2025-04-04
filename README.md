# 🧠 Modelo Lógico - E-commerce

Este repositório contém o **modelo lógico** de um sistema de e-commerce, com foco em representar as principais entidades envolvidas no processo de compra, pagamento e entrega.

---

## 📌 Entidades e Relacionamentos

- **Cliente**
  - Pode ser **Pessoa Física (PF)** ou **Pessoa Jurídica (PJ)**, mas nunca os dois ao mesmo tempo.
  - Contém dados como: nome, e-mail, telefone, CPF/CNPJ, etc.

- **Pedido**
  - Relacionado a um cliente.
  - Possui data, status e valor total.
  
- **Pagamento**
  - Um pedido pode ter **mais de uma forma de pagamento** cadastrada.
  - Cada pagamento tem um tipo e um status.

- **Entrega**
  - Cada pedido tem uma entrega associada.
  - A entrega possui um **status** (ex: em transporte, entregue) e um **código de rastreio**.

---

## 📄 Arquivo Disponível

- `Universidade.mwb`: Contém a estrutura lógica em SQL com as tabelas, atributos e relacionamentos.

---

## 🚀 Objetivo do Projeto

Este desafio faz parte de uma atividade de construção de modelos de banco de dados. O foco aqui foi refinar um modelo simples de e-commerce, adicionando requisitos reais de negócio.

---

## 🛠️ Como contribuir

1. Faça um fork do projeto
2. Crie uma nova branch (`git checkout -b feature/NomeDaFeature`)
3. Commit suas alterações (`git commit -m 'Adiciona nova feature'`)
4. Dê push na sua branch (`git push origin feature/NomeDaFeature`)
5. Abra um Pull Request

---

## 📃 Licença

Este projeto está sob a licença MIT.
