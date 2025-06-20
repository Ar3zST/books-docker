# AluraBooks - Ambiente Docker

Este repositório contém um arquivo `docker-compose.yml` para subir rapidamente o ambiente da aplicação **AluraBooks**, utilizando o MongoDB.

## 🚀 Como rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/alurabooks-docker.git
   cd alurabooks-docker

2. Suba os containers:
docker-compose up

3. Acesse a aplicação no navegador:
http://localhost:3000
O MongoDB será iniciado automaticamente como dependência da aplicação.

🧱 Serviços

Serviço	    Descrição	                      Porta
alurabooks	Aplicação Node.js da Alura	    3000:3000
mongodb	    Banco de dados MongoDB (v4.4)	  interno

🗂️ Estrutura esperada

📁 projeto/

├── docker-compose.yml

└── README.md
Não é necessário clonar o código da aplicação — a imagem aluradocker/alura-books:1.0 já vem com tudo pronto.

✅ Requisitos
Docker
Docker Compose

📌 Observações
Os serviços estão conectados por uma rede Docker customizada chamada compose-bridge.
A imagem aluradocker/alura-books:1.0 já inclui a aplicação configurada para se comunicar com o MongoDB.

