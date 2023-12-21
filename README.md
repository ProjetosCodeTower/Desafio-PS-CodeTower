# Desafio de Projetos CodeTower

Primeiramente, obrigado pelo seu interesse em fazer parte da Code Tower! Abaixo você encontrará todas as informações necessárias para iniciar o seu teste.

## Descrição da tarefa
A partir de um protótipo do figma e um esquema relacional, produzir um frontend e um backend em formato de API.
O sistema de notas, onde o usuário deve conseguir criar, editar e deletar notas. Crie um repositório para seu projeto e faça commit nele, o mesmo deverá ser compartilhado conosco ao final do prazo.

## FRONTEND
Especificamente sobre o frontend, deverá ser dinâmico, single page application, e deve consumir a api de forma que seja capaz de utilizar todas operações. O frontend deve ser fiel ao protótipo, os tamanhos não precisam ser iguais ao do figma, mas precisa parecer visualmente. Antes de ir para a aplicação principal, é necessário que seja cadastrado um usuário(Pessoa) e as notas a serem mostradas e criadas na aplicação devem ser relacionadas a essa Pessoa. Não será cobrado tela esteticamente bonita para esse cadastro, essa requisição para registrar uma pessoa pode ser feita diretamente, sem ser exibida na tela, com um useEffect por exemplo, também pode ter uma tela ou até mesmo prompts do javascript para cadastrar. Não é necessário implementar autenticação, somente guarde de alguma forma qual é a pessoa que está fazendo a requisição.
![Prototipo da aplicação](https://media.discordapp.net/attachments/1186869708650197094/1186870275611050044/Home.png?ex=6594d214&is=65825d14&hm=9fd2c32525bffbdb2ce3b26a5d086052f696a472210227a8e46a3ef8d23a25c0&=&format=webp&quality=lossless&width=701&height=498)
<br>https://www.figma.com/file/tyjvaxvfspC39MzKJASxtU/Untitled?type=design&node-id=2%3A1696&mode=design&t=czd52zkP5ImSduoi-1

## BACKEND
Já a API, deve ser MVC e preferencialmente no padrão Rest API. A API deve ter todas as operações relacionadas a notas, e suas respectivas rotas. É necessário utilizar algum tipo de Banco de Dado, podendo ser SQLite ou um Banco de Dados externo. Não é necessário implementar uma autenticação.

O esquema relacional a ser seguido:
![Esquema Relacional](https://cdn.discordapp.com/attachments/1105596238746886144/1186456052632391753/image.png?ex=6593504e&is=6580db4e&hm=10d6d4008639680eb253eb924b6fb8468beb62d1d748272fb0e8e3ab7f92b5d8&)

Boas práticas e código limpo também serão avaliados.
O desafio pode ser realizado na linguagem/framework que preferir, porém é estritamente necessário que seja um front e uma api. É diferencial que seja feito em Nextjs para o front, Django Rest Framework para o back e Postgresql, já que são stacks utilizadas na Code Tower, mas faça com as tecnologias que tiver domínio. A aplicação, tanto frontend quanto backend devem ser Dockerizadas. É preferível finalizar do que seguir a risca todos os requisitos..

