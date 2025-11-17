# Minimal API em .NET 9

Este projeto é uma Minimal API desenvolvida em **.NET 9**, criada com o objetivo de demonstrar uma estrutura simples e funcional para criação de endpoints utilizando o modelo minimalista introduzido nas versões mais recentes do .NET.

---

## 🚀 Tecnologias Utilizadas

* **.NET 9**
* **C# 12**
* **Minimal API**
* **Swagger / OpenAPI** (se configurado)

---

## 📂 Estrutura do Projeto

```
minimal-api/
│
├── Api/
│   ├── Program.cs
│   ├── Properties/
│   │   └── launchSettings.json
│
└── minimal-api.sln
```

---

## ▶️ Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU_USUARIO/minimal-api
```

### 2. Entrar no diretório do projeto

```bash
cd minimal-api/Api
```

### 3. Restaurar dependências

```bash
dotnet restore
```

### 4. Executar a aplicação

```bash
dotnet run
```

🔹 Caso a porta 5004 esteja ocupada, execute em outra porta:

```bash
dotnet run --urls "http://localhost:5010"
```

---

## 🌐 Endpoints Disponíveis (Exemplo)

### GET /

Retorna uma mensagem simples.

```json
{
  "message": "API funcionando!"
}
```

### POST /clientes (exemplo, se implementado)

Cria um novo cliente.

### GET /clientes/{id}

Retorna os dados de um cliente por ID.

> Obs.: Adapte esta seção conforme seus endpoints reais.

---

## ⚙️ Configuração de Porta

A porta padrão pode ser encontrada em:

```
Properties/launchSettings.json
```

Você pode alterar assim:

```json
"applicationUrl": "http://localhost:5010"
```

---

## 🧪 Testes

Use ferramentas como:

* **Postman**
* **Insomnia**
* **Swagger UI** (se habilitado)

---

## 📜 Licença

Este projeto está sob a licença MIT.

---

## 👤 Autor(a)

**Loren Eisfeld Conde Rosa**

LinkedIn: [https://www.linkedin.com/](https://www.linkedin.com/in/loren-eisfeld-conde-rosa-4a12171b5)
GitHub: [https://github.com/](https://github.com/Lorenconde)

Desafio de Projeto DIO Akad
