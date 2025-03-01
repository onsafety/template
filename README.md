# 🔧 Projeto - Sistema de Gestão de Pessoas

## 📄 Descrição

Este projeto foi desenvolvido como parte do **Processo Seletivo Dev - OnSafety**. Trata-se de uma aplicação para gestão de pessoas, permitindo CRUD (Create, Read, Update, Delete) de usuários.

## 🔧 Tecnologias Utilizadas

- **Java XX**
- **Spring Boot X.x**
- **Spring Data JPA** (Hibernate)
- **MySQL** (Banco de Dados Relacional)
- **Swagger** (Documentação da API)
- **JUnit / Mockito** (Testes automatizados)
- **Docker** (Containerização)
- **Git/GitHub** (Controle de versão)

## 🛠þ Como Rodar o Projeto

### **1️⃣ Requisitos**

Certifique-se de ter instalado:

- **Java X**
- **Maven**
- **Docker** (Opcional, para subir o banco de dados rapidamente)

### **2️⃣ Clonar o Repositório**

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### **3️⃣ Configurar o Banco de Dados**

Caso tenha **Docker**, basta rodar:

```bash
docker-compose up -d
```

Se preferir, crie um banco **MySQL** manualmente e atualize o `application.properties`.

### **4️⃣ Rodar a Aplicação**

```bash
mvn spring-boot:run
```

A API estará disponível em: `http://localhost:8080`

## 📊 Endpoints da API

A documentação da API pode ser acessada via **Swagger**:

```
http://localhost:8080/swagger-ui.html
```

### **Exemplo de Requisições**

#### **Criar uma Pessoa**

```json
POST /pessoas
{
  "nome": "João Silva",
  "email": "joao@email.com",
  "cpf": "12345678900"
}
```

#### **Listar Pessoas**

```json
GET /pessoas
```

#### **Atualizar uma Pessoa**

```json
PUT /pessoas/{id}
{
  "nome": "João Pedro Silva",
  "email": "joaopedro@email.com"
}
```

#### **Deletar uma Pessoa**

```json
DELETE /pessoas/{id}
```

## 🛠þ Testes Automatizados

Para rodar os testes unitários:

```bash
mvn test
```

## 🌟 Diferenciais Implementados (Opcional)

-

## 📢 Contato

Caso tenha dúvidas, entre em contato:

- **E-mail:** [seuemail@email.com](mailto\:seuemail@email.com)
- **LinkedIn:** [seu-perfil](https://www.linkedin.com/in/seu-perfil)
- **GitHub:** [seu-usuario](https://github.com/seu-usuario)

---

🎯 *Este projeto faz parte da fase prática do processo seletivo da OnSafety.*

