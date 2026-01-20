# 🌐 Hospedagem de Aplicação no Azure App Service

Este repositório contém a documentação do projeto prático do Bootcamp da **DIO (Digital Innovation One)**. O objetivo foi provisionar e realizar o deploy de uma aplicação web utilizando a plataforma PaaS (Platform as a Service) da Microsoft.

## 📋 Cenário
A necessidade de hospedar uma aplicação web escalável sem a complexidade de gerenciar servidores (VMs). A solução escolhida foi o **Azure App Service**, que permite focar no código enquanto a Azure gerencia a infraestrutura.

## 🛠️ Tecnologias Utilizadas
* **Azure App Service:** Serviço de hospedagem PaaS.
* **Runtime Stack:** Node.js (LTS) em ambiente Linux.
* **Azure Portal:** Para gerenciamento e monitoramento de recursos.

## 🚀 Passo a Passo da Implementação

### 1. Provisionamento do Recurso
Foi criado um Web App na região `East US 2` (para conformidade com a subscrição acadêmica), utilizando a stack Node.js.

### 2. Validação
O serviço foi implantado com sucesso, gerando uma URL pública acessível globalmente via HTTPS, garantida pelo certificado SSL padrão do Azure.

## 📸 Evidências

### Aplicação em Execução (Browser)
![Site no Ar](https://github.com/CleristonJr/dio-lab-azure-app-service/blob/main/site-no-ar.png?raw=true)
*Página default do App Service confirmando que o servidor está respondendo na porta 80/443.*

### Painel de Gerenciamento (Azure)
![Painel Azure](https://github.com/CleristonJr/dio-lab-azure-app-service/blob/main/painel-app-service.png?raw=true)
*Visão geral do recurso, mostrando status "Running" e URL de acesso.*

## 🧠 Aprendizados
* **Serverless/PaaS:** Diferença prática entre subir uma VM e usar um App Service (muito mais rápido e simples).
* **Domínios:** O Azure fornece automaticamente um subdomínio `azurewebsites.net` para testes rápidos.
* **Escalabilidade:** O plano escolhido permite, futuramente, escalar verticalmente (Scale Up) ou horizontalmente (Scale Out) com poucos cliques.

---
## 👨‍💻 Autor
Cleriston Jr.
www.linkedin.com/in/cleriston-júnior-ba419218b
