# Estruturas de Repetição

## FOR
```
let pontosDeVida = 0

for(let i = 1; i <= 10; i++){
  pontosDeVida += 1
  console.log("Tomou remédio " + i)
}

console.log(pontosDeVida + " Pontos de vida")
```

## WHILE
```
let contador = 0
while (contador < 3){
  console.log("Olá")
  contador++
}
```

## DO WHILE 
```
let contador = 3
do {
  console.log("Olá")
  contador++
} while (contador < 3)
```

- A principal diferença entre WHILE e DO WHILE é que no DO WHILE o programa vai ser executado pelo menos uma vez, independente da condição, e só depois essa condição será testada
