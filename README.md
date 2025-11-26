# Bootcamp 01 Qualiters Club
Teste de API Rest do manual a CI/CD

## O que é
Este repositório foi criado para o bootcamp do Teste de API Rest

## Tecnologias utilizadas
- Postman
- node version v24.11.1
- newman v6.2.1
- newman-reporter-html

## Documentação

- Doc da API: [Consulte Swagger](https://serverest.dev/#/)

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://www.nodejs.tech/pt-br/download)
- Segundo: realize a instalação do newman de forma global, usando o terminal ou prompt de comando com o seguinte comando:
```
 npm install -g newman
```
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
 npm install -g newman-reporter-html
```

## Como rodar os testes

### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo Newman

- Abra o console (de preferencia)
- Execute a seguinte linha de comando para rodar os testes:
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
-Execute os teste com relatórios:
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontra.


## Entre em contato
email: anglica.viana@yahoo.com.br

Rede Social: www.linkedin.com/in/angelicaviana-qa

