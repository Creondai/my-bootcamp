# Dados úteis sobre o módulo

## GIT

Download -> https://git-scm.com/
Markdown -> https://www.markdownguide.org/

### Comandos importantes

git init [^1]: Registra o git na pasta em que está
git init <directory> [^1]: Registra o git na pasta endereço que for especificado.
git add <file> [^1]: Adiciona ao arquivo especificado o status de tracked pronto pra commit.
git add <directory> [^1]: Adiciona a pasta especificado o status de tracked pronto pra commit.
git add -A [^1]: Adiciona em todos os arquivos o status de tracked pronto pra commit.
git add . [^1]: Adiciona em todos os arquivos da pasta, o status de tracked pronto pra commit.
git commit -m "commit message" [^1]: Realiza o commit de todos os itens prontos e registra uma mensagem título para o commit.
git status [^1]: Lista quais os arquivos e pastas que estejam prontos, despreparados para o commit e também os que não estão sendo monitorados.
git remote -v [^1]: Lista as conexões remotas com os repositórios e mostra a url de cada uma.
git remote add origin <url> [^1]: cria uma conexão com o repositório remoto. "origin" é um apelido que representa a url.
git push <url remoto> main [^1]: envia toda a branch para o repositório do github
git pull <url remoto> [^1]: puxa toda a branch do repositório remoto para o repositório local.
