# Trabalhando com Funções 

### Exemplo 1
#### torrar()
```
function torrar(){
 console.log("torrando pão")
 injetarPao()
}

function injetarPao(){
	console.log("preparando para injetar o pão")
    console.log("finalizado")
}
```

### Exemplo 2
#### saudar()
```
function saudar(nome) {
  console.log("Olá, " + nome + "! Como você está?");
}

saudar("Pedrinho"); // Vai dizer: Olá, Pedrinho! Como você está?
saudar("Mariana"); // Vai dizer: Olá, Mariana! Como você está?
```

## Funções com Parâmetro

### Exemplo 3 
#### dizerOla()
```
function dizerOla(nome) {
  console.log("Olá, " + nome + "! Como você está?");
}
dizerOla("Pedrinho"); // Vai dizer: Olá, Pedrinho! Como você está?
dizerOla("Mariana"); // Vai dizer:  Olá, Mariana! Como você está?
```

### Exemplo 4
#### calcularIdade()
```
function calcularIdade(nome, anoNascimento) {
  let idade = 2023 - anoNascimento;
  console.log(nome + " tem " + idade + " anos!");
}

calcularIdade("Pedrinho", 2010); // Vai mostrar: Pedrinho tem 13 anos!
calcularIdade("Mariana", 2008); // Vai mostrar: Mariana tem 15 anos!
```

## Funções com Retorno

### Exemplo 5
#### getFirstName()
```
let userName = getFirstName("Carlos-Almeida-Juanito-Gargalo", "-")
console.log("Seja bem vindo " + userName)

userName = getFirstName("Felipe Silva Han Solo", " ")
console.log("Seja bem vindo " + userName)

function getFirstName(name, splitChar){
	let firstName = name.split(splitChar)[0]
    return firstName
}
```

### Exemplo 6
#### somar()
```
function somar(numero1, numero2) {
  return numero1 + numero2;
}

let resultado = somar(5, 3); // A função vai dar de presente: 5 + 3 = 8
console.log("A soma é: " + resultado); // Vai mostrar: A soma é: 8
```



