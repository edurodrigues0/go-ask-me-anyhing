# AMA (Ask Me Anything) - Backend

## Apresentação

Este repositório contém o backend do projeto **AMA (Ask Me Anything)**, uma plataforma interativa desenvolvida durante a **Semana Tech Go React** da Rocketseat. O objetivo do projeto é criar um ambiente onde usuários possam enviar perguntas em tempo real e receber respostas instantâneas, oferecendo uma experiência de comunicação direta e envolvente.

## Tecnologias Utilizadas

O backend do projeto foi construído utilizando as seguintes tecnologias:

- **Golang**: Escolhido pela sua eficiência e desempenho, Golang foi a linguagem principal utilizada para desenvolver o backend, garantindo uma aplicação rápida e escalável.

- **Postgres**: Utilizado como banco de dados relacional, o Postgres foi escolhido por sua robustez e confiabilidade na gestão de dados estruturados.

- **Docker**: Adotado para containerização do ambiente de desenvolvimento e produção, facilitando a configuração e garantindo consistência no deploy da aplicação.

- **WebSockets**: Implementado para permitir a comunicação em tempo real entre o servidor e os clientes, permitindo que perguntas e respostas sejam atualizadas instantaneamente.

## Como Rodar o Backend

### Pré-requisitos

- **Docker** instalado na máquina.
- **Go** instalado na máquina.

### Passos para Configuração e Execução

1. **Clone o repositório:**

   ```bash
   git clone git@github.com:edurodrigues0/fundamentos-go.git
   cd ama-backend
  ```

2.  **Configure as variáveis de ambiente:**

```bash
# Crie um arquivo .env na raiz do projeto e copie e cole o conteudo do arquivo .env.example
```

3. **Suba os containers com Docker:**

Certifique-se de que o Docker está rodando e execute o seguinte comando:

```bash
docker-compose up -d
```

4. **Rode migrations:**

```bash
go generate ./...
```

5. **Acesse a aplicação:**
O backend estará rodando na porta 8080. Você pode acessar a API através de http://localhost:8080.

## Conclusão
O backend do projeto AMA (Ask Me Anything) foi desenvolvido utilizando tecnologias robustas e modernas como Golang, Postgres e Docker, proporcionando uma base sólida e eficiente para a aplicação. A integração com WebSockets permite atualizações em tempo real, garantindo que a experiência do usuário seja fluida e responsiva. Este projeto não só demonstrou a potência dessas tecnologias em conjunto, mas também possibilitou a criação de uma plataforma interativa de alta performance.