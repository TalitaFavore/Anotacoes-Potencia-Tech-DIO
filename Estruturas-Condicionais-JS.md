# Estruturas Condicionais

## IF
### Exemplo 1
```
let ehLigado = false

if(ehLigado){
    console.log("Executou comando")
}
```

### Exemplo 2
```
let possuiOvos = true
let itensComprados = ""
if (possuiOvos){
  itensComprados = "Leite"
}
console.log("Item comprado: "+ itensComprados)
```

## IF/ELSE
### Exemplo 3
```
let possuiOvos = false
let itensComprados = ""
if (possuiOvos){
  itensComprados = "Leite"
} else {
  console.log("Passou na sessão de congelados")
  itensComprados = "Lasanha Congelada"
}
console.log("Item comprado: "+ itensComprados)
```
## IF/ ELSE IF/ ELSE
### Exemplo 4
```
let nivelDeFome = 1

if (nivelDeFome === 1){
  console.log("Pouca fome")
} else if (nivelDeFome === 2) {
  console.log("Muita fome")
} else {
  console.log("Você comeria mais que o Pica-pau")
}
```
## SWITCH CASE
### Exemplo 5
```
let fruta = "Pêra"

switch (fruta){
  case "Laranja":
  console.log("Suco de laranja")
  break

  case "Banana":
  console.log("Vitamina de Banana")
  break

  case "Maçã":
  console.log("Suco de Maçã")
  break

  default:
  console.log("Suco genérico")

}
```
### Exemplo 5.1
```
let fruta = "Morango"

switch (fruta){
  case "Laranja":
  console.log("Suco de laranja")
  break

  case "Banana":
  case "Morango":
  console.log("Vitamina")
  break

  case "Maçã":
  console.log("Suco de Maçã")
  break

  default:
  console.log("Suco genérico")
}
```

### Exemplo 5.2
```
let fruta = 1

switch (fruta){
  case 1:
  console.log("Suco de laranja")
  break

  case 2:
  console.log("Vitamina")
  break

  case 3:
  console.log("Suco de Maçã")
  break

  default:
  console.log("Suco genérico")
}
```

### Exemplo 5.3
```
let fruta = "Banana"

switch (fruta){
  case "Laranja":
  console.log("Suco de laranja")
  console.log("Segunda mensagem")
  break

  case "Banana":
  case "Morango":
  console.log("Vitamina de " + fruta)
  break

  case "Maçã":
  console.log("Suco de Maçã")
  break

  default:
  console.log("Suco genérico")
}

for (let contador = 0; contador < 4; contador++){
    console.log(contador)
    console.log("Aumentando o contador")
  }
```
