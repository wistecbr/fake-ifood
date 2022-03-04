# Comandos do Git para subir alterações

## Adiciona todos os arquivos que foram alterados e/ou excluidos

```
    git add .
```

## Criamos um COMMIT

```
    git commit -m "Descrição da alteração"
```

## Envia as alterações 

```
    git push origin BRANCH
```

## Respostas se tudo der certo

```
    PS C:\Users\Wisley Alves\Desktop\Praticas Senac\fake_ifood> git add .
    PS C:\Users\Wisley Alves\Desktop\Praticas Senac\fake_ifood> git commit -m "Crie o index e adicionei documentação"
    [main e048f58] Crie o index e adicionei documentação
    2 files changed, 31 insertions(+), 51 deletions(-) 
    rewrite index.html (91%)
    PS C:\Users\Wisley Alves\Desktop\Praticas Senac\fake_ifood> git push origin main
    Enumerating objects: 7, done.
    Counting objects: 100% (7/7), done.    
    Delta compression using up to 4 threads
    Compressing objects: 100% (4/4), done.
    Writing objects: 100% (4/4), 582 bytes | 194.00 KiB/s, done.
    Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
    remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
    To https://github.com/wistech7l/fake-ifood.git
    2cc517e..e048f58  main -> main

````