# execicioszinhos
function convert(metro){
  var cent=metro*100
  var mili=metro*1000
  return  metro +' metros é igual á ' +cent+ ' centímetros e ' + mili +' milímetros'
}
console.log(convert(1))

const frutas = ['maçã', 'banana'];
frutas.push('laranja','uva')
console.log(frutas)
const numeros = [1, 2, 3, 4, 5];
var ultimonúmero=numeros.splice(4)
console.log(numeros)

const estudante ={
  idade:6,
  endereco:[{
    rua: 'loimoeiro',
    numero:34,
    bairro:'são josé'
  
  },{
     rua: "bahia",
     numero: "38",
     bairro: "paulina"
            }
  ]
  
}
// vai adicionar mais isso dentro do endereço
estudante.endereco.unshift({
    rua: "Nome da rua",
     numero: "500",
     bairro: "Santa Cruz"
 })
console.log(estudante)
console.log(estudante.endereco[2].rua)
estudante.idade=7
console.log(estudante)

delete estudante.idade
console.log(estudante)
