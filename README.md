# 🚀 Web App com Docker Compose

Aplicação web simples desenvolvida em **Node.js** com **Express**, containerizada com **Docker** e orquestrada via **Docker Compose**. Ideal para estudos, provas de conceito e ambientes de desenvolvimento local.

---

## 📌 Funcionalidades

* Página web institucional simples
* Backend em Node.js + Express
* Servidor de arquivos estáticos (HTML e CSS)
* Endpoint de *health check*
* Containerização com Docker
* Orquestração e gerenciamento com Docker Compose

---

## 🛠 Tecnologias Utilizadas

* Node.js 20
* Express
* Docker
* Docker Compose
* HTML5 / CSS3

---

## ▶️ Como Executar o Projeto

### ✅ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

* **Docker**
* **Docker Compose** (ou Docker Desktop, que já inclui o Compose)

---

### 🧩 Passo a Passo

#### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/vini20041994/web-app-docker-compose
```

#### 2️⃣ Acessar a pasta do projeto

```bash
cd web-app-docker-compose
```

#### 3️⃣ Subir a aplicação com Docker Compose

Este comando irá construir a imagem e iniciar os containers automaticamente:

```bash
docker compose up --build
```

> 💡 Dica: para executar em segundo plano (*modo detached*), use:
>
> ```bash
> docker compose up -d --build
> ```

---

### 🌐 Acessando a aplicação

Após a inicialização dos containers, a aplicação estará disponível em:

```
http://localhost:3000
```

---

### ⛔ Encerrando a aplicação

Para parar e remover os containers:

```bash
docker compose down
```

---

## 📌 Observações

* Projeto voltado para **estudo e prática** de Docker e Docker Compose
* Estrutura simples e fácil de adaptar para novos cenários
* Ideal como base para aplicações web containerizadas

---

## 👤 Autor

**Vinicius Joacir dos Anjos**


Projeto desenvolvido para estudo de **Docker**, **Docker Compose** e **aplicações web em Node.js**.
