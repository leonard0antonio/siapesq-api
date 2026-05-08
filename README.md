![GitHub repo size](https://img.shields.io/github/repo-size/leonard0antonio/siapesq-api?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/leonard0antonio/siapesq-api?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/leonard0antonio/siapesq-api?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/github/issues/leonard0antonio/siapesq-api?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/github/issues-pr/leonard0antonio/siapesq-api?style=for-the-badge)

![Demo da aplicação](Demo.png)

> API desenvolvida para o projeto Siapesq, atuando como intermediária com o banco de dados. Hospedada no Render, é simples, baseada em JSON, mas totalmente funcional e completa.

## 📖 Introdução

O **siapesq-api** é uma parte essencial do ecossistema do projeto Siapesq, assumindo o papel de intermediar a comunicação entre a interface (frontend) e o banco de dados. Apesar da sua arquitetura ser bastante simples e estruturada com base num ficheiro `server.json` (utilizando `json-server`), a API está **100% funcional e completa**, atendendo a todas as necessidades de fornecimento, atualização e persistência de dados da aplicação principal. Além disso, o projeto já se encontra em produção, hospedado e a correr na plataforma **Render**.

## 🎯 Resumo de Funcionalidades

As principais características desta API incluem:

- **Intermediação de Dados:** Atua como a ponte direta e eficiente entre o cliente e os dados armazenados.
- **Simplicidade e Eficiência:** Utiliza uma abordagem leve baseada em `server.json`, permitindo respostas ágeis sem a sobrecarga de um sistema de banco de dados complexo.
- **Totalmente Funcional:** Apesar da simplicidade técnica, oferece todos os endpoints (CRUD) necessários para o funcionamento completo do projeto Siapesq.
- **Deploy Ativo:** Configurada e hospedada com sucesso na plataforma Render, pronta para receber requisições em ambiente de produção (cloud).

### Ajustes e melhorias

O projeto encontra-se na sua versão funcional e completa, com as tarefas principais concluídas:

- [x] Estruturação dos dados no ficheiro `server.json`
- [x] Criação e configuração dos endpoints da API
- [x] Deploy finalizado na plataforma Render
- [ ] Implementação de rotas de segurança ou validações extras (se necessário no futuro)
- [ ] Possível migração para um banco de dados robusto caso a aplicação escale (futuro)
