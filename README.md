# Desafio de Projeto – Projeto Lógico de Banco de Dados (E-commerce)

## 📌 Descrição do Desafio

O objetivo deste desafio é **replicar e refinar a modelagem lógica de um banco de dados para o cenário de e-commerce**, conforme apresentado ao longo do curso. O projeto deve respeitar as definições de **chaves primárias**, **chaves estrangeiras** e **constraints**, bem como os relacionamentos definidos no modelo **EER (Enhanced Entity-Relationship)**.

Além da replicação do modelo, é necessário **aplicar os refinamentos propostos no módulo de modelagem conceitual**, adaptando o esquema lógico para atender a requisitos mais realistas do cenário de negócio.

---

## 🧱 Modelagem e Implementação

O projeto contempla as seguintes etapas:

- Replicação da **modelagem lógica** do banco de dados de e-commerce
- Criação do **Script SQL** para gerar todo o esquema do banco
- Persistência de dados (*INSERTs*) para testes
- Implementação de **consultas SQL mais complexas**, além das demonstradas no desafio guiado

---

## 🧮 Consultas SQL Desenvolvidas

Foram elaboradas queries SQL contemplando as cláusulas abaixo:

- Recuperações simples com `SELECT`
- Filtros utilizando `WHERE`
- Criação de **atributos derivados** por meio de expressões (`CASE`, cálculos, etc.)
- Ordenação dos dados com `ORDER BY`
- Agrupamentos com `GROUP BY` e filtros com `HAVING`
- Junções (`JOIN`) entre tabelas para fornecer análises mais completas dos dados

📌 As cláusulas podem estar presentes em mais de uma query e **não há um número mínimo de consultas**.

---

## 🎯 Objetivo do Refinamento do Modelo

Conforme proposto no desafio, o modelo foi refinado considerando os seguintes pontos:

- **Cliente Pessoa Física (PF) e Pessoa Jurídica (PJ)**  
  Uma conta pode ser PF ou PJ, mas **não pode conter ambas as informações**.

- **Pagamento**  
  Um cliente pode ter cadastrada **mais de uma forma de pagamento**.

- **Entrega**  
  A entidade entrega possui **status** e **código de rastreio**, possibilitando o acompanhamento do pedido.

---

## 🏆 Projeto

- [Projeto - Primeiro Banco de Dados](https://github.com/guimazza-ai/projeto-primeiro-banco-dados/blob/main/Projeto/Primeiro%20projeto%20com%20banco%20de%20dados%20SQL.sql)

