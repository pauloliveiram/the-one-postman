# Testes na API do "O Senhor dos Aneis" - Postman

## Sobre o projeto

Essa é uma aplicação de testes automatizados em uma API com informações sobre a saga de livros e filmes "O Senhor dos Aneis". Os testes foram aplicados em todos os endpoints da API, cujos resultados são disponibilizados em relatório gerado pelo Allure.

Além disso, foi desenvolvida uma pipeline no Github Actions para que os testes sejam executados e o relatórios sejam gerados a cada push ou pull request na branch main do repositório.

## Link da API
https://anapioficeandfire.com/

## Tecnologias utilizadas

- Postman
- Allure Report
- Github Actions

## Endpoints testados

- [GET] Listar todos os livros (/books)
- [GET] Listar um livro específico (/books/id)
- [GET] Listar todos os personagens (/characters)
- [GET] Listar um personagem específico (/characters/id)
- [GET] Listar todas as casas (/houses)
- [GET] Listar uma casa específica (/houses/id)

## Relatório gerado
![image](https://github.com/pauloliveiram/the-one-postman/assets/39312072/c45f1674-d3ce-4792-a5e4-6dccff1ae197)

## Como executar os testes

1) Clonar o repositório
2) Importar os arquivos "postman_environment.json" e "postman_collection.json" no Postman
3) Enviar as requisições dos endpoints
   - Ao enviar a requisição, os testes são executados			

# Autor

Paulo Oliveira


