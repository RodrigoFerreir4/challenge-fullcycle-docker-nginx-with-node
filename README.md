# Desafio Nginx e Node.js

Neste desafio, você deve usar o Nginx como proxy reverso para uma aplicação Node.js que adiciona um nome ao banco de dados MySQL. Quando um usuário acessar o servidor, o Nginx deve fazer uma chamada para a aplicação Node.js, que adiciona um nome ao banco de dados e retorna uma página HTML com o título "Full Cycle Rocks!" e a lista de nomes cadastrados.

Para executar o desafio, basta clonar este repositório, instalar o Docker e o Docker Compose em sua máquina, e executar o comando `docker-compose up -d` O Nginx estará disponível na porta 8080. Acesse http://localhost:8080 em seu navegador para testar a aplicação.
