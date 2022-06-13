# Projeto Docker Todo List! 🐳

---

## 🐋 Sumário

- [Requisitos do projeto]

  - [Comandos docker]
      - [1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`]
      - [2. Inicie o container `01container`]
      - [3. Liste os containers filtrando pelo nome `01container`]
      - [4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele]
      - [5. Remova o container `01container` que está em andamento.]
      - [6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.]
      - [7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.]
      - [8. Pare o container `02images` que está em andamento.]
  - [Dockerfile]
      - [9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.]
      - [10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.]
      - [11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.]
  - [Bônus]
    - [Docker-compose]
      - [12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.]

---

## 🐋 Habilidades Desenvolvidas

  * Usar comandos dockers no CLI - Interface de linha de comando;
  * Criar um contêiner Docker para uma aplicação de front-end;
  * Criar um contêiner Docker para uma aplicação de back-end;
  * Criar um contêiner Docker para uma aplicação de testes;
  * Orquestrar os três contêineres utilizando o Docker compose.

---

## 🐋 O que foi desenvolvido

"conteinerização" das aplicações de frontend, backend e testes, e criação de uma conexão entre elas orquestrando seu funcionamento.
 Criação das imagens nas aplicações e configura-las com o docker-compose.


