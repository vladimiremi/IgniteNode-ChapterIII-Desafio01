#  Chapter III - Desafio 01: Database Queries :rocket: :purple_heart:

## :dart: Objetivo

Realizar consultas no banco de dados com o TypeORM de três formas:

- ORM
- Query Builder
- Raw Query

## :white_check_mark: Requisitos

### Repositórios da aplicação

#### UsersRepository
- [x] findUserWithGamesById
- [x] findAllUsersOrderedByFirstName
- [x] findUserByFullName

#### GamesRepository
- [x] findByTitleContaining
- [x] countAllGames
- [x] findUsersByGameId

### Específicação dos testes

#### UsersRepository
- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

#### GamesRepository
- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id


## :computer: Instalação ##
```bash
# Clone este repositório
$ git clone https://github.com/vladimiremi/IgniteNode-ChapterIII-Desafio01

# Entre na pasta
$ cd IgniteNode-ChapterIII-Desafio01

# Instale as dependências
$ yarn ou yarn install

# Crie o container de banco de dados
$ docker-compose up

# Execute os testes da aplicação
$ yarn test
```

## ❗ Deletando o container ##
Depois que executar os testes é interessante fazer a remoção do container:
```bash
# parar o container
$ docker-compose stop

# deletar o container
$ docker-compose rm
