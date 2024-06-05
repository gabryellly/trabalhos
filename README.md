# funcoes
function imprimirOlaMundo() { console.log("Ola mundo!") } imprimirOlaMundo()

function imprimeNome(nome){ alert('Ola${nomeUser}') } let nomeUser = " " nomeUser = prompt("digite seu nome") imprimeNome(nomeUser)

function minhaFuncao(variavel) { return variavel * 5 }

console.log(minhaFuncao(10)) console.log(minhaFuncao(2))

let textoDoUsuario = prompt("Insira um texto");

const outraFuncao = function(texto) { return texto.toLowerCase().includes("cenoura") }

const resposta = outraFuncao(textoDoUsuario) console.log(resposta)

let String = "gaby" let number = 15 let String ("gaby") + number ("15") String + ("estudante") console.

function imprimirOlaMundo() { console.log("Ola mundo!") } imprimirOlaMundo()

function imprimeNome(nome){ alert('Ola${nomeUser}') } let nomeUser = " " nomeUser = prompt("digite seu nome") imprimeNome(nomeUser)

function minhaFuncao(variavel) { return variavel * 5 }

console.log(minhaFuncao(10)) console.log(minhaFuncao(2))

let textoDoUsuario = prompt("Insira um texto");

const outraFuncao = function(texto) { return texto.toLowerCase().includes("cenoura") }

const resposta = outraFuncao(textoDoUsuario) console.log(resposta)

let String = "gaby" let number = 15 let String ("gaby") + number ("15") String + ("estudante") console.

function minhaFuncao(Array){ return Array * 10 }

console.log(minhaFuncao(10)) console.log(minhaFuncao(9))

alert NOME alert IDADE alert ENDEREÇO alert PROFISSÃO console.log NOME = String(prompt "qual seu nome") IDADE = Number(prompt "qual sua idade") ENDEREÇO = String(prompt "onde voce mora") PROFISSÃO = String(prompt "qual sua profissão") let resultado Eu sou [NOME], tenho [IDADE] anos, moro em [ENDEREÇO] e sou [PROFISSÃO]

//Online Javascript Editor for free // Write, Edit and Run your Javascript code using JS Online Compiler

//Declaração de variáveis em escopo global (Boas Práticas) //let arrayNumerico = [] //let tamanhoArray = 0

//Função de ordenação por Força Bruta //function arrayBruteForceSort(){ // let temp = 0 //for(let i = 0; i < tamanhoArray - 1; i++){ // for(let j = 0; j < tamanhoArray - 1; j++){ // if(arrayNumerico[j] > arrayNumerico[j + 1]){ // temp = arrayNumerico[j] // arrayNumerico[j] = arrayNumerico[j + 1] // arrayNumerico[j + 1] = temp //} //} //} //}

//Inicialização de valores //arrayNumerico = [1,0,3,2,5,4,7,6,9,8,11,10,13,12,15,14,17,16,19,18,21,20,23,22,25,24,27,26,29,28,31,30,33,32,35,34,37,36,39,38,41,40,43,42,45,44,47,46,49,48,51,50] //tamanhoArray = arrayNumerico.length //Compara tempo de execução*/

//Declaração de Variáveis (Boas Práticas) let arrayNumerico = [] let tamanhoArray = 0

//Função de ordenação por Inserção function arrayInsertionSort(){ let temp = 0 for (let i = 1; i < tamanhoArray; i++){ temp = arrayNumerico[i] j=i-1 //arrayNumerico[0] = temp while (temp < arrayNumerico[j]){ arrayNumerico[j+1] = arrayNumerico[j] j-- } arrayNumerico[j+1] = temp } }

//Inicialização de valores arrayNumerico = [1,0,3,2,5,4,7,6,9,8,11,10,13,12,15,14,17,16,19,18,21,20,23,22,25,24,27,26,29,28,31,30,33,32,35,34,37,36,39,38,41,40,43,42,45,44,47,46,49,48,51,50] tamanhoArray = arrayNumerico.length //Compara tempo de execução let inicio = performance.now() arrayInsertionSort() let fim = performance.now() //Escreve array ordenado no console e tempo de execução console.log("A ordenação foi executava em: ",(fim-inicio)," ms") console.log(arrayNumerico)

let inicio = performance.now() arrayBruteForceSort() let fim = performance.now() //Escreve array ordenado no console e tempo de execução console.log("A ordenação foi executava em: ",(fim-inicio)," ms") console.log(arrayNumerico)
