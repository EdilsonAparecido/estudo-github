
## inicia um repositório git
```
git init
```

## adiciona um arquivo para ser comitado
```
git add <nome do arquivo>
```

## verifica o estado dos arquivos
```
git status
```

## salvo o estado dos arquivos
```
git commit -m "<Comentário>" 
```

## vincula meu git com github
```
git remote add origin <url> 
```

## criar ramificações e mudar para ela
```
git checkout -b <main> 
```

## enviar
```
git push origin main 
```

## puxar
```
git pull origin main 
```

## clonar repositorio do github
```
git clone <url> <nome da pasta>
```

## utilizado para fundir as histórias do github para git
```
git pull origin main --allow-unrelated-histories
```

## utilizado para vincular o git com github
```
git remote get-url origin
```

## limpar cache
```
git rm --cached . -rf
```
