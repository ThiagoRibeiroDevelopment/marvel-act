#Marvel ACT
Aplicativo utilizando as APIs da Marvel que faça a busca e listagem de personagens

Aplicativo hospedado no serviço gratuito de Heroku, 
link para acesso: https://marvelact.herokuapp.com/app/home.html#/

## 1. Configurar o projeto no Heroku
  1 - Criar uma conta em Heroku (www.heroku.com)
  2 - Ferramenta a ferramente de interface do Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli
  3 - Acessar qualquer terminal e autenticar o Keruku login com os passos:
      - heroku login
        heroku: Enter your login credentials
      - Email [seu e-mail]: 
      - Password: ********
      Logged in as email...@.com.br

  4 - Para criar o projeto
      - heroku create marvelact
        Creating ⬢ marvelact... done
      https://marvelact.herokuapp.com/ | https://git.heroku.com/marvelact.git

## 2. Configuração de ambiente e depências
1. npm install
2. npm --version (para verificar se deu certo a instalação do node)
3. npm install gulp
4. npm install -g gulp-cli

## 3. Consumo das APIs Marvel
1. APIs Marvel:  https://developer.marvel.com/docs
2. Criar key public e private

## 4. Subindo para o Heroku
    - git init
      Initialized empty Git repository in /../marvelact/.git/
    - git remote add heroku https://git.heroku.com/marvelact.git
    - git push heroku master

