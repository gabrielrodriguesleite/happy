# Projeto Happy

Melhore e depois arruine o humor de uma SPA utilizando a API de piadas [geek](https://github.com/sameerkumar18/geek-joke-api).

1. A aplicação inicia com uma tela de login.
2. O formulário de login deve conter os campos de e-mail e senha (validação para e-mail e mínimo de 8 caracteres para a senha).
3. Após o login, a primeira rota (URL do navegador) é [/inicial](http://localhost:3000/inicial), e possui uma tela nem feliz, nem triste :|
4. O primeiro clique na tela deve alterar a rota para [/triste](http://localhost:3000/triste), e por consequência torná-la 100% triste :(
5. Um clique na tela triste deve alterar a rota para [/poker-face](http://localhost:3000/poker-face) e chamar uma piada randômica do backend, para ser apresentada em uma modal.
6. A tela deverá progressivamente melhorar o seu humor enquanto lemos a piada (ou mais de uma) para ela :)
7. A modal com a piada só poderá ser fechada após a tela estar 100% feliz com a sua vida novamente, e a rota para isso deverá ser [/feliz](http://localhost:3000/feliz).
8. Fechada a modal, a SPA volta a sua indecisão [/inicial](http://localhost:3000/inicial) sobre o seu humor, sua vida, o universo e tudo mais :|

## Clonar o projeto do github

No terminal execute o comando:

```sh
git clone https://github.com/gabrielrodriguesleite/happy.git
```

## Iniciar o projeto utilizando docker-compose

No terminal execute o comando:

```sh
docker-compose up
```
