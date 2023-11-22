## Fluxo  remoto
Após realizar toda a configuração do  git é hora de usa-lo no dia-a-dia.  
Ao trabalhar em equipe o primeiro comando a fazer é o git pull p/ pegar  a última versão do código (getLatestVersion).  
Outro comando importante é o git fetch que remove branch que não existem mais.
```
git pull
git fetch -p
```

Após organizar os arquivos com git add e git commit é o momento de envia-los para o repositório remoto
```
git push origin main
git push --force-with-lease (apos um amend)
```