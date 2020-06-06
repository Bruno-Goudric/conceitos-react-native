<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>


## Features
Para o desenvolvimento do projeto foi utilizada uma stack com as seguintes tecnologias:

- 💹 **React Native** — é uma biblioteca Javascript criada pelo Facebook. É usada para desenvolver aplicativos para os sistemas Android e IOS de forma nativa
- 💹 **Axios** - é um cliente HTTP, que funciona tanto no browser quanto em node
## Desafio

Durante as aulas de Front-end com ReactJs foi abordado os seguintes temas:

- ** `Arquitetura React Native`**
- ** `Configurando SDK`** link - https://react-native.rocketseat.dev/
- ** `Criando novo projeto`**
- ** `Diferenças do ReactJS`**
- ** `Listando projetos da API`**
- ** `Criando novos projetos`**

## Requisitos

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.
## Getting started
yarn dev

### Instalação - ANDROID
Clone o projeto em seu computador. Para instalar basta seguir o passo a passo abaixo:
```bash
https://github.com/Bruno-Goudric/conceito-react-native.git 
cd conceito-rect-native
yarn install
react-native run-android
```

### Instalação - IOS
Clone o projeto em seu computador. Para instalar basta seguir o passo a passo abaixo:
```bash
https://github.com/Bruno-Goudric/conceito-react-native.git 
cd conceito-rect-native
pod install
react-native run-ios
```

### Validando os Testes da Aplicação
Clone o projeto em seu computador. Para instalar as dependências e executar o **Servidor** (modo test) execute:

```bash
  https://github.com/Bruno-Goudric/conceito-react-native.git 
  cd conceito-rect-native
  yarn install ou pod install
  yarn test
```

### Específicação dos teste

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Caso você tenha dúvidas quanto ao que são os testes, e como interpretá-los, dé uma olhada em **[nosso FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-desafios).**

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.
