
# Tabela Fipe

Como principal desafio esse projeto consiste em utilizarmos Java e Spring Boot na criação de uma aplicação que roda via termianl para realizar a consulta de determinado carro, moto ou caminhão, na qual essas informações estão sendo consumidas da Fipe API.




## Stack utilizada

**Back-end:** Java, Spring Boot


## Opções de consultas

URL BASE = https://parallelum.com.br/fipe/api/v1/

A aplicação possuí suporte para filtros, podendo alterar a URL, desejando listar determinado modelo de carro, seu rescpectivo ano e faixa de preço. Na nossa aplicação de inicio foi optado por listar todos os tipos de veículos a qual o usuário deseja consultar, consequentemente ao buscar a opção de veículo disponibilizamos o filtro de ano e preço.

```java
*** OPÇÕES ***
CARRO
MOTO
CAMINHÃO  
                      
DIGITE UMA DAS OPÇÕES PARA CONSULTAR:      

```


## Autores

- [@kaio-d](https://github.com/kaio-d)


## Documentação da API

#### Retorna todos os itens

```http
  GET https://parallelum.com.br/fipe/api
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | Para utilizar essa API não é necessário uma Key |

#### Retorna um item

```http
  GET https://parallelum.com.br/fipe/api/v1/
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |




## Referência

- [FIPE API](https://deividfortuna.github.io/fipe/v2/)


## Etiquetas


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Licença

[MIT](https://choosealicense.com/licenses/mit/)

