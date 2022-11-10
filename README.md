<p align="center">
    <img src="https://user-images.githubusercontent.com/42224962/201028378-8837205c-3524-4305-85e4-d60660d40bfc.svg" height="100px"/>
</p>

# Índice

1. [O que é?](#o-que-e?) 🤔
2. [Tecnologias](#tecnologias) ⚛️
3. [Processo](#processo) 🚵
    1. [Aula 1](#aula-1)
    2. [Aula 2](#aula-2)
    3. [Aula 3](#aula-3)
    4. [Aula 4](#aula-4)
    5. [Aula 5](#aula-5)
4. [Prints](#prints) 📸
    1. [Web](#web) 💻
    2. [Back-end](#back-end) 🎲
    3. [Mobile](#mobile) 📱
5. [Conclusão](#conclusão) 📖
    1. [O que eu aprendi?](#o-que-eu-aprendi?) 🎓
    2. [Agradecimentos](#agradecimentos) 🙏
    3. [Contatos](#contatos) ☎️


# O que é?

NLW Copa foi um evento organizado pela Rocketseat, com o objetivo de criar um Bolão da Copa do Mundo 2022, tendo 1 página web, 1 aplicação mobile e 1 sistema back-end com banco de dados.
Para ter acesso ao design detalhado de todo o projeto, aqui está o link do [Figma](https://www.figma.com/file/4KdvhgtQi8SbLVxIqGWmAu/Bol%C3%A3o-da-Copa-(Community)?node-id=0%3A1).

<p display="flex">
    <img src="https://user-images.githubusercontent.com/42224962/201030177-8965ef2a-28c3-45de-bcb3-6c6d87d51dc9.png" height="300px"/>
    <img src="https://user-images.githubusercontent.com/42224962/201030185-b3e21809-4b0e-4823-9433-34c963607183.png" height="300px"/>
</p>

# Tecnologias

- **Front-end**
  - Web
    - Typescript
    - ReactJS
    - NextJS
    - TailwindCSS
    - PostCSS
    - Axios
   - Mobile
      - Typescript
      - React Native
      - Expo Go
      - Babel
      - Axios
- **Back-end**
  - Typescript
  - Fastify
  - Prisma
  - Zod

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,tailwind,vite,sqlite,react,prisma,nodejs,nextjs,figma" />
  </a>
</p>

# Processo

## Aula 1
- **Setup do Back-end**
    - Fastify (Micro frame-work semelhante ao Express)
    - Prisma (Responsável pela comunicação com o banco de dados; inserção, remoção, listagem)
    - Banco de Dados (SQL Lite, ou qualquer outro banco de dados, já que o fastify suporta-os)
    - Diagrama ERD (Entidades e relacionamentos, modelagem de dados)
        - <p><img src="https://user-images.githubusercontent.com/42224962/201043336-e2e2fe7a-acd9-49b6-af2d-548b8b65b932.svg" height="500px"/></p>
    - Contagem de bolões (Rotação no back-end)
- **Front-end**
    - React
        - Componentes: reusabilidade, manuntenção
        - Propriedades
    - NextJS (Server Side Rendering)
    - React Native
        - Aplicações mobile pra IOS e ANDROID usando JavaScript

## Aula 2
- **Back-end**
    - Estrutura do banco e relacionamentos
    - Criando seed do banco de dados
    - Criação de novo bolão
    - Contagem de usuários
    - Contagem de palpites
- **Aplicação Web**
    - Layout de aplicação
    - Conexão com API
    - Criação do bolão
    
## Aula 3
- **Interface da Autenticação**
    - Utilizando SVG como Componente no React Nativa para exibir ologo (svg-transformer)
    - Tipando SVG
    - Criando o componente de Button
    - Finalizando a interface do SignIn
- **Contexto de Autenticação**
    - Criando o contexto
    - Criando hook para compartilhar contexto
    - Compartilhando dados através do contexto
- **Autenticação com Google**
    - Conceito de OAuth (Solicitação)
    - Instalando o expo auth
    - Instalando o expo web browser
    - Configurar OAuth com Google
    - Implementando autenticação Google
- **Interface para criar e encontrar o bolão**
    - Compartilhando os demais componentes de aplicação
    - Finalizando a interface New
    - Reaproveitar a estrutura do New para criar a interface Find
- **Interface de bolões**
## Aula 4
- Back-end
    - Separando arquivos de rotas
    - Criação de usuário (Access Token do Google)
    - Geração de JWT
    - Validação de JWT
    - Rota de perfil (/me)
    - Criação de bolão com usuário logado
    - Entrar em um bolão
    - Bolões que eu participo
    - Detalhes de um bolão
    - Listagem de jogos de um bolão
    - Criação de um palpite
- Finalização do app mobile
    - Navegação
        - Instalando o React Navigation
        - Criando as rotas
        - Customizando a Bottom Tabs
        - Navegando pela aplicação
        - Tipagem das rotas
    - Integração com back-end
        - Instalando o Axios
        - Configurando acesso a API
        - Buscando os dados do usuário no back-end
        - Inserindo o token no header das requisições
        - Redirecionando usuário para rotas da aplicação
## Aula 5
- New
    - Criar um novo bolão
- Pools
    - Listando os bolões criados
    - Utilizando mensagem de toast
    - Utilizando Flatlist
    - Utilizando o List Empty Component
    - Recarregando a lista quando o foco volta para a interface
- Find
    - Entrar em um bolão pelo código
- Details
- Guesses
- Variável de ambiente
- Ranking
 
# Prints

## Web

![image](https://user-images.githubusercontent.com/42224962/201038091-1a971420-ffd6-42e6-a5ee-cfd27b0bf321.png)

## Back-end

![image](https://user-images.githubusercontent.com/42224962/201039760-74c1b3ae-4a12-420e-975e-3f71db8be0b9.png)

## Mobile

<p display="flex">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039891-b982967a-4928-421a-9cc4-0f238c1581ec.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039893-af651fc7-2bcc-4f5d-adbb-a664cef0b1dd.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039896-0116e89b-7204-46a4-88a8-744fd3a5eecc.png">
</p>

<p display="flex">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039883-aa4a2110-9941-41e8-b6cf-ade1ea343add.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039886-80ae90db-c7d3-452f-80cd-c2a7c0f0132e.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039890-875a5f28-7371-4760-a738-d8b1575d4444.png">
</p>

<p display="flex">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039875-b5ee4677-7598-4de4-b420-864ba392d91a.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039877-3661e123-c612-489d-97bf-18fb96be9e02.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039881-0d9bdbe6-7c58-4f98-b346-409406fd4ac9.png">
</p>

<p display="flex">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039864-d8d56ef9-d409-4d07-b705-0c180972b7c2.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039870-5f8b0c9a-2208-4e2c-beeb-64dd04d19b68.png">
  <img width="250px" src="https://user-images.githubusercontent.com/42224962/201039873-e3091174-495f-4dc0-a5af-5eb08809ddcc.png">
</p>

# Conclusão

## O que eu aprendi?

Nesse NLW, eu nunca aprendi tanto em tão pouco tempo... conceitos de React, utilização do framework NextJS, React Native para mobile, banco de dados, 
livrarias como o Fastify, Prisma, estrutura de banco de dados e relacionamentos, conexão com API, interface de autenticação (mais complicado haha), estilização
com tailwindcss e o próprio React Native.

Porém acho que além desses conceitos, o mais importante que eu aprendi foi a importância do foco, organização e persistência, porque é fácil pra quem vê de fora pensar que
estamos apenas copiando e colando código, quando na verdade surgem inúmeros erros e bugs no caminho que nos frustam e desmotivam, nesses obstáculos param os menos motivados, 
mas quem são nesses momentos que se criam verdadeiros programadores, que vão atrás de resolver o erro, seja por conta própria seja perguntando na comunidade. 

## Agradecimentos

Não posso deixar de agradecer imensamente a Rocketseat, que proporciona eventos com TANTO conhecimento atual, ensino metodológico e interação com a comunidade. Tudo isso de graça, 
um dia essa semente que eles plantaram retornará! Pois irei adquirir meu primeiro emprego como desenvolvedor web e aí sim poderei comprar o curso Ignite deles com maior prazer hahaha. <3

## Contatos

Se você se interessou pelo meu esforço e tem alguma oportunidade profissional para me recomendar: 

- (91) 98445-9458
- helio.lucio.jr@hotmail.com
- [Linkedin](https://www.linkedin.com/in/heliolj/)
