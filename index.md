1. variaveis
let estaChovendo = true
const meuNome = "Mayk"


2. Tipos de Dados 
string
""
''

Number 
12 - Intefer ( + - )
3.2 - Float ( + - )

Boolean
true ou false
const marioDeDezoito = false

undefined - indefinido


3. Operadores 
Atribuições (ex: =)
Atribuir valor 
let n1 = 12
let n2 = 3

Artiméticos (ex: * / +-)
Calculos matematicos simples 

Concatenação de string (+)

Comparação (ex: > < =)
transforma a expressão em true ou false
const maiorQue = 1 > 2 // false
const igualA = 1 = 1 // true

4. Condicional (if/else)
const idade = 17
const maiorDeDezoito = idade >= 18

if(marioDeDezoito) {
  alert("Pode tirar carteira de motorista")
  } else {
    alert("nâo pode tirar")
  }

  5. Estrutura de dados 
  Array - Vetor - Lista
  Array ------- 0   1 2 3 
  const temperaturas = [23.3,32.2,1,5]

  Object 
  const pessoa = {
    nome = "Mayk",
    idade: 38,
    filhos: ["K", "E", "J", "L", "G"]
  }

  console.log(pessoa.filhos[2])

  6.Fuction
  1. Criação 
  function nomeDaFunca  () {
    console.log('código dentro da função')
  }

  2. Execução 
  nomeDaFuncao()

  Parâmetros
  function soma(a, b) {
    console.log(a + b)
  }

  soma(34, 45)
  soma(90, 54)

  Retorno 
  function soma(a, b){
    return a + b
  }

  const multiplica = soma(2, 2) * 4
  console.log(multiplica)

  console.log(soma(2, 2))

  7. Extensões da linguagem (ex.: Math, Dath ...)

  Math.random() - numero aleatorio entre 0 e 1
  Math.floor(1.2) - arredonda para baixo
  Math.ceil(1.2) - arredonta para cima
  Math.PI - mostra o n PI

  8. DIM - Document Object Model

  window
  window.alert("alerta")
  Document
  document.write("texto")
  manipular elementos
  document.documentElement.style.background = "black"

