# Anotações

## Comandos utilizados

### git clone link_do_repositório_do_git

O`git clone` é um utilitário de linha de comando que é usado para selecionar um repositório existente e criar um clone ou cópia do repositório de destino.

O `git clone` é usado sobretudo para apontar para um repositório existente e fazer um clone ou cópia deste repositório no novo diretório, em outro local.

### git init

O comando `git init` cria um novo repositório do Git.

### git config

O comando `git config` é a função conveniente usada para definir valores de configuração do Git em projetos de nível global ou local.

```
git config --global user.name #exibe
```

```
git config --local user.email <email> #altera
```

```
git config --global user.name <name>
```

* Aliases

```
git config --global alias.st status 
git config --global alias.co checkout 
git config --global alias.br branch 
git config --global alias.up rebase 
git config --global alias.ci commit
```

* Como usa

```
git <alias>
EX: git st
```



### git status

O comando `git status` é usado para examinar o estado atual do repositório e pode ser usado para confirmar uma promoção de `git add`.

### git diff

### git add .

O comando `git add` adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, `git add` não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar `git commit`.



### git commit -m "msg"

O comando `git reset` é usado para desfazer um commit ou captura de tela preparada.

### git commit -am "add Informações dos comandos"

Faz git add e git commit -m ao mesmo tempo

### git push origin main

O `git push` é utilizado para enviar as alterações com commit para repositórios remotos para colaboração. Assim os outros membros da equipe podem acessar um conjunto de alterações salvas.

### git reset

