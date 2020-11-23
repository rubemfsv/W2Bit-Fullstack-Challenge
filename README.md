## W2Bit - Fullstack Challenge

Se você chegou até aqui, parabéns! Agora vamos avaliar suas habilidades técnicas com um desafio prático.

Você será avaliado por sua capacidade de escrever códigos legiveis, simples e de fácil manutenção.

### Instruções
* Nome do Projeto: W2Bit Bus Station 
* Objetivo: Criar uma API RESTful capaz de gerenciar os ônibus de sua frota e as rotas, e uma interface em React Native para poder interagir com a API.
* Tecnologia: React Native e Node.js com banco de dados relacional.
* Entrega: Crie um repositório pessoal para o back e um para o front, siga as instruções abaixo, sinalize o término e envie o link dos repositórios) o link do deploy da API, e a documentação no insomnia para testar sua api. 

### Recomendações
* Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
* Tenha sempre um mindset de usabilidade, escalabilidade e colaboração.
* A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
* O design/estrutura do código da aplicação deve ser production ready.
* Tenha em mente os conceitos de SOLID, KISS, YAGNI e DRY.
* Use boas práticas de programação.
* Você pode usar bibliotecas como Express, mas queremos que a solução de arquitetura seja sua, portanto não use frameworks que impõem uma arquitetura específica.
* Utilize PostgreSQL como banco de dados.
* Faça deploy no Heroku.
* Você pode fazer utilizando Expo ou React Native Cli, fica por sua decisão, mas justifique sua escolha.
* O design da aplicação fica por sua decisão, nos surpreenda!
* Inclua no seu readme os desafios/problemas com os quais você se deparou durante a execução do projeto.

## Challenge!

Você foi contratado para fazer um app para donos de frotas de ônibus, onde os usuários poderão criar uma conta, se autenticar utilizando um token JWT e poderão adicionar seus ônibus e rotas. Após cadastrar o ônibus, ele poderá cadastrar uma nova viagem e relacionar um ônibus a uma viagem (não é possível criar uma viagem sem ônibus).

* A Sua API deverá ser capaz de:
  * Cadastrar um novo usuário
  * Se autenticar utilizando JWT
  * Cadastrar um novo ônibus
  * Listar todos os ônibus cadastrados
  * Listar os dados de um ônibus
  * Alterar dados de um ônibus
  * Excluir um ônibus
  * Adicionar uma nova viagem
  * Listar todas as viagens
  * Listar uma viagem em específico
  * Alterar dados da viagem
  * Excluir viagem

* Sua interface deve ser capaz de:
  * Cadastrar o usuário (primeiro lista os estados, após selecionar, lista as cidades do estado)
  * Fazer login
  * Cadastrar, editar e remover ônibus
  * Listar todos os ônibus da frota e os detalhes de um ônibus em específico caso selecionado
  * Cadastrar, editar e remover viagems
  * Listar todas as viagens e os detalhes de uma viagem em específico
  
* O cadastro do usuário deve ter os seguintes campos:
  * Nome
  * Foto
  * Estado e cidade
  * Senha
  * Confirmação de senha

* O cadastro do ônibus deve ter os seguintes campos:
  * Placa
  * Ano
  * Modelo
  * Numero de assentos

* O cadastro da viagem deve ter os seguintes campos:
  * Destino
  * Horário de partida
  * Duração
  * Ônibus locado para a viagem
  
### O que avaliaremos
* Você será avaliado pela qualidade do código, legibilidade e pelo modo que implementou as funcionalidades.
* Você é livre para tomar as decisões técnicas com as quais você se sente mais confortável.

### Happy coding!
