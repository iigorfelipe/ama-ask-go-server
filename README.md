# AMA | Any ask anything

Plataforma interativa de perguntas e respostas em tempo real. O backend, desenvolvido em Go com Websockets e PostgreSQL, suporta a criação de salas virtuais, enquanto o frontend em React proporciona uma interface dinâmica onde os participantes podem fazer, reagir e ordenar perguntas, oferecendo uma experiência fluida e envolvente.


## 🛠️ Tecnologias Utilizadas

- [Go](https://github.com/topics/go)
- [Docker](https://github.com/topics/docker)
- [Tern](https://github.com/jackc/tern)
- [Websocket](https://github.com/gorilla/websocket)
- [SQL](https://github.com/topics/sql)
- [PostgreSQL](https://github.com/topics/postgresql)

## 🚀 Como executar o projeto

1. Clone o repositório:
```bash
git clone git@github.com:iigorfelipe/ama-ask-go-server.git
```

2. Entre na pasta do projeto:

```bash
cd ama-ask-go-server
```

3. Renomeie o arquivo `env.example` para `.env`:

```bash
mv env.example .env
```

4. Suba os serviços usando Docker Compose:

```
docker-compose up -d
```

5. Execute as migrações do banco de dados:

```
go generate ./gen
```

6. Inicie o servidor:
```
go run ./cmd/ws/main.go
```

⚠️ O comando acima executará apenas o backend (servidor). Para se conectar à aplicação web, siga os passos do repositório abaixo:

- [Repositório da aplicação Web](https://github.com/iigorfelipe/ama-ask-react-web)


## Autor

@Igor Felipe

[![Linkedin Badge](https://img.shields.io/badge/-LinkdedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/iigor-felipe/)](https://www.linkedin.com/in/iigor-felipe/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:iigorfelipe@gmail.com)](mailto:iigorfelipe@gmail.com)
