# 🚀 Web App com Docker Compose

Aplicação web simples desenvolvida em Node.js e Express, 
containerizada com Docker e orquestrada com Docker Compose.
Ideal para estudos, provas de conceito e ambientes de desenvolvimento.

---

## 📌 Funcionalidades

- Página web institucional simples
- Backend em Node.js + Express
- Servidor de arquivos estáticos (HTML e CSS)
- Endpoint de health check
- Containerização com Docker
- Subida e gerenciamento via Docker Compose

---

## 🛠 Tecnologias Utilizadas

- Node.js 20
- Express
- Docker
- Docker Compose
- HTML5 / CSS3

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

- Docker
- Docker Compose

### Passos

```bash
# Clonar o repositório
git clone <url-do-repositorio>
cd web-compose

# Subir a aplicação
docker compose up -d --build
