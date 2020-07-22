# pontential-crud
Potencial para um crud


# Objetivo do teste
Desenvolver uma API JSON RESTful em ​PHP​, que utilize os métodos (​GET​, ​POST​, ​PUT​,
DELETE​).

# Especificação
Monte uma base de desenvolvedores com a seguinte estrutura:

```
nome: varchar
sexo: char
idade: integer
hobby: varchar
datanascimento: date
```

Utilize o ​banco de dados​ de sua preferência para armazenar os dados que a API irá
consumir.

# API endpoints

```
GET /developers
Codes 200
```
Retorna todos os desenvolvedores

```
GET /developers?
Codes 200 / 404
```
Retorna os desenvolvedores de acordo com o termo passado via querystring e
paginação

```
GET /developers/{id}
Codes 200 / 404
```
Retorna os dados de um desenvolvedor

```
POST /developers
Codes 201 / 400
```
Adiciona um novo desenvolvedor

```
PUT /developers/{id}
Codes 200 / 400
```
Atualiza os dados de um desenvolvedor

```
DELETE /developers/{id}
Codes 204 / 400
```
Apaga o registro de um desenvolvedor

# DIFERENCIAL PARA VAGA SENIOR -  Frontend
UI/UX fica a critério do desenvolvedor porém deverá ser SPA (single-page
application) e atender o consumo de todos endpoints da API 

# Entrega
A aplicação deve possuir um script para geração das tabelas no banco de dados

Após finalizado enviar os arquivos em resposta ao e-mail com explicação de como
configurar e/ou executar scripts necessários, ou enviar link do projeto no github com
explicação no README

