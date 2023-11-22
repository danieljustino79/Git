Git sistema distribuído de controle de versão que cria um repositório sobre um diretório do sistema operacional.

## Comandos básicos
```
git -v
git init
git add .
git status
git commit -m "mensagem de commit"
git commit --amend
git log
```

### Ciclo de vida
Os arquivos monitorados pelo git possuem 4 life-cycle.
* untracked
* unmodified
* modified
* staged

### git clone
Download dos arquivos de um repositório remoto p/ uma pasta local, neste caso não terá maiores configurações de linha de comandos (em ambiente Windows).
```
git clone https://github.com/danieljustino79/Markdown.git
```

## Configuração
Para realizar a interação com um repositório remoto (github, gitlab, aws ou MS devops) será necessário ter um user.name e user.email configurados.
```
git config --global user.name
git config --global user.email

git config --global user.name "nome de usuario"
git config --global user.email "email@e.com"
```

### git remote add origin
Caso o repositório tenha sido criado localmente e precisa ser enviado p/ um repositório remoto, será necessário executar alguns comandos.
```
git branch -M main
git remote add origin https://github.com/danieljustino79/Git.git
git push -u origin main
```

## Outros comandos
```
git log --author="sam"
git shortlog
git show
git show 71bc6dc7 (8 dígitos)
git diff
git diff --name-only
git remote
git remote -v
```

[fluxo remoto](fluxo-remoto.md)