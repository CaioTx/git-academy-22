# git-academy-22

## git init
inicialização de um projeto:
```
git init
```

## Configurações iniciais
```bash
git config --global user.name "username"
# https://github.com/CaioTx/git-academy-22.git
git congit --global user.name "user@email.com"
# https://github.com/CaioTx/git-academy-22.git

```
> Para deixar na main
```
git branch -m main
```
## Controle de alterações
Para visualizar as alterações feitas, vamos usar:
```bash
git status
TOUCH readme.md
```
## Criando commits
Primeiramente precisamos adcionar as mudanças e enfim 'commitar':
> utilize o ponto para adicionar todas alterações do projeto
```bash
git add .
git commit -m "descricao das alteracoes"
# "criei o arquivo README.md"
```

## Branches
Podemos ramificar o código usando branches para criar uma nova, executamos:
```bash
git switch --create <nome-da-nova-branch>
# or
git checkout -b <nome-da-nova-branch>
```
- Listando braches criadas:
```bash
git branch
```

- Apagando branch
```bash
git branch -D <nome-da-branch>
```

## GitHub
Adicionando um remote origin:
```bash
git remote add origin https://github.com/user/repo-name.git
```
- ubindo alterações
```bash
git push origin <nome-da-branch>
# caso a branch nao exista no GitHub use:
git push -u origin <nome-da-branch> 
# ele criara a branch no GitHub
```
```
# echo "# git-academy-22" >> README.md
# git remote add origin https://github.com/CaioTx/git-academy-22.git
# teste 




