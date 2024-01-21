# Operadores

## Operadores Aritméticos

### Exemplo 1
#### Adição e Subtração (+ -)
```
let idade = 30
console.log("Valor da variável: " + idade)
idade = 30 + 6
console.log("Adição: " + idade)
idade = 30 - 6
console.log("Subtração: " + idade)
```

### Exemplo 2
#### Subtração (-)
```
let codigoDoProduto = 1023
let codigoExato = codigoDoProduto - 1000
console.log(codigoExato)
console.log(codigoDoProduto-codigoExato)
```

### Exemplo 3
#### Multiplicação (*)
```
let precoProduto = 100.99
let valorComTaxa = precoProduto * 2
console.log(valorComTaxa)
```

### Exemplo 4
#### Multiplicação (*)
```
let multiplicador = 4
let multiplicando = 12
let produto = multiplicador * multiplicando
console.log("O resultado da multiplicação é: " + produto)
```

### Exemplo 5
#### Divisão (/)
```
let notaDoMercado = 50
let pessoasParaDividir = 2
console.log("Divisão: " + notaDoMercado/pessoasParaDividir)
```

### Exemplo 6
#### Módulo ou Resto da divisão (%)
```
let calculo = 10%3
console.log("Módulo: " + calculo)
```

# Operadores de Incremento e Decremento
```
let contador = 1
console.log(contador)
//incremento
contador++
console.log(contador)
contador--
//decremento
console.log(contador)
```

# Operadores de Atribuição
```
let preco = 10
preco += 5 // é igual a preco = preco + 5
console.log(preco)
preco -= 5 // é igual a preco = preco - 5
console.log(preco)
```

## Precedência de Operadores ou Associação de Operadores
```
let resultado = 2 * (5 + 5)
console.log(resultado)
```
- A expressão (5 + 5) é avaliada primeiro devido aos parênteses, conforme as regras de precedência de operadores. Neste caso, os parênteses forçam a adição a ser feita antes da multiplicação.

## Operadores de Comparação ou Operadores Relacionais

### Exemplo 1
```
let numero = "1"
console.log(numero === 1)
```

- = é atribuição
- == é para comparar o valor
- === é para comparar o valor e formato
- !== é diferente?

### Exemplo 2
```
let marca = "Apple"
let resultado = marca !== "Samsung"
console.log(resultado)
```

### Exemplo 3
```
let cpfBloqueado = "123.456.789-00"
let cpfUsuario = "111.111.111-11"
let ehCPFBloqueado = cpfUsuario === cpfBloqueado
console.log("O usuário está barrado? " + ehCPFBloqueado)

let CPFPermitido = "222.222.222-00"
let CPFDoUsuario = "222.222.222-22"

let ehBloqueado = CPFDoUsuario !== CPFPermitido

console.log("É um usuário inválido? " + ehBloqueado)
```

### Exemplo 4
```
let idadeMinima = 18
let idadeUsuario = 17
let idadePermitidaValida = idadeUsuario >= idadeMinima
console.log(idadePermitidaValida)
```

### Exemplo 5
```
let idadeDeCorte = 50
let idadeDoUsuario = 50
let resultadoEhTerceiraIdade = idadeDeCorte <= idadeDoUsuario
console.log(resultadoEhTerceiraIdade)
```

## Operadores Lógicos

### Exemplo 1
#### AND (&&)
```
let idade = 17
let vistoVerificado = true
let resultado = ((idade>=18) && (vistoVerificado === true))
console.log(resultado)
```

### Exemplo 2
#### AND (&&)
```
let moedasColetadas = 100
let item = "Estrela"
let resultado = ((moedasColetadas >=100) && (item === "Estrela"))
console.log(resultado)
```

### Exemplo 3
#### OR (||)
```
let tempo = "Chuva"
let item = "Estrela"
let podeSair = ((tempo !== "Chuva") || (item === "Guarda-chuva"))
console.log("O personagem pode sair? " + podeSair)
```

### Exemplo 4
#### NOT (!)
```
let tempo = "Sol"
let resultado = tempo !== "Chuva"
console.log("O tempo é diferente de chuva? " + resultado)
```

- NOT (!) - nega uma afirmação - muda a polaridade de uma variável

### Exemplo 5
#### NOT (!)
```
let tempo = "Sol"
let horario = 8
let resultado = !((tempo !== "Chuva") && (horario > 6))
console.log("O tempo é diferente de chuva? " + resultado)
```
