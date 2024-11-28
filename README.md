# Cloud_projeto2024.2

- Link do deploy: https://d37p7vyk5oh1q2.cloudfront.net/docs

**# FastAPI JWT Auth API - Pokémon Fetcher

## Desenvolvido por Pedro Ventura

### Descrição do Projeto
Este projeto é uma API REST desenvolvida com FastAPI, que implementa autenticação com JWT (JSON Web Tokens). A aplicação possui três endpoints principais:

1. Cadastro de novos usuários.
2. Login para autenticação e geração de token JWT.
3. Consulta de um Pokémon aleatório utilizando a [PokéAPI](https://pokeapi.co/).

O projeto foi dockerizado com dois serviços: um para a API REST e outro para um banco de dados Postgres. A imagem da API foi publicada no Docker Hub, permitindo execução sem necessidade de build local.

---

### Como Executar a Aplicação

1. **Clone o Repositório**  
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2.	Certifique-se de que o Docker está instalado
  Baixe e instale o Docker em sua máquina.
	
3.	Inicie os serviços com o Docker Compose
  Certifique-se de que o arquivo compose.yaml está na raiz do projeto. Em seguida, execute:

  ```bash
  docker compose up
  ```

4.	Acesse a API
  A API estará disponível em http://localhost:8000. A documentação interativa (Swagger) pode ser acessada em http://localhost:8000/docs.

---

Endpoints da API

1. Cadastro de Usuário

	- URL: /registrar
	- Método: POST

2. Login

	- URL: /login
	- Método: POST

3. Consulta de Pokémon

	- URL: /consultar
	- Método: GET

---

- Vídeo de Demonstração: 
- Imagem no Docker Hub:
- Localização do Arquivo compose.yaml: 
**
