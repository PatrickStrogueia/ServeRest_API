
---

# Bootcamp #01 Qualiters Club  
**Teste de API Rest: do manual ao CI/CD**  

## 📌 Sobre  
Este repositório foi criado para o Bootcamp de Teste de API Rest, abordando desde a execução manual até a automação com CI/CD.  

## 🚀 Tecnologias utilizadas  
- **Postman** (versão desktop)  
- **Node.js** (v20.18.0)  
- **Newman** (v6.2.1)  
- **Newman Reporter HTML**  

## 📑 Documentação  
- **Análise Técnica:** [Análise/](./Analise)  
- **Documentação da API:** [Swagger](https://serverest.dev/#/)  

## ⚙️ Configuração do ambiente  

### 1️⃣ Instalar o Node.js  
Baixe e instale o Node.js em seu computador: [Download Node.js](https://nodejs.org/en/download)  

### 2️⃣ Instalar o Newman (globalmente)  
Execute o comando abaixo para instalar o Newman globalmente:  
```sh
npm install -g newman
```  
Mais informações: [Newman npm](https://www.npmjs.com/package/newman)  

### 3️⃣ Instalar o Newman Reporter HTML (opcional)  
Para gerar relatórios em HTML:  
```sh
npm install -g newman-reporter-html
```  
Mais informações: [Newman Reporter HTML](https://www.npmjs.com/package/newman-reporter-html)  

## 🧪 Executando os testes  

### 🔹 Via Postman (web ou desktop)  
1. Importe a **collection** e o **environment** no Postman  
2. Execute os testes manualmente ou automatizados  

### 🔹 Via Newman (CLI)  

#### Rodando os testes no terminal  
```sh
newman run GH_ServeRest.postman_collection.json -e ServeRest_test.postman_environment.json -r cli
```  

#### Rodando os testes com relatório HTML  
```sh
newman run GH_ServeRest.postman_collection.json -e ServeRest_test.postman_environment.json -r cli,htmlextra
```  

### 📊 Visualizando o relatório  
Se optou por gerar o relatório HTML (`htmlextra`), um arquivo será criado com os resultados dos testes. Basta abrir o arquivo gerado no navegador para visualizar os detalhes das execuções.  

## 📞 Contato  
- **E-mail:** patrickdealcantara@gmail.com  
- **LinkedIn:** [Patrick Strogueia](https://www.linkedin.com/in/patrick-strogueia/)  

---
