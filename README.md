# PROVA
 Questão 1- 
function cumprimentar(nome, idade){
  console.log(`Olá, ${nome}, sua idade é ${idade}`)
}

cumprimentar('Ana', 20)
cumprimentar('Pedro', 16)
cumprimentar('João', 17)



questão 3-
// 1. Crie uma função chamada registrarPedido que receba cliente, prato, mesa e idade
function registrarPedido (cliente, prato, mesa, idade) {
  return {
    cliente: "Bruno",
    prato: "Lasanha",
    mesa: 2,
    idade: 17
  };


let pedidos = (1,2,3)

// 3. Adicione 3 pedidos ao array usando a função criada
console.log(registrarPedido("Ana", "Hambúrguer", 1,10));
console.log(registrarPedido("Bruno", "Lasanha", 2, 17));
console.log(registrarPedido("Carlos", "Feijoada", 3, 65));

// 4. Crie uma função chamada classificarIngresso que retorna o tipo com base na idade
function classificarIngresso(idade) {
  if (idade < 12) {
    return "Infantil";
  } else if (idade >= 12 && idade <= 17) {
    return "Adolescente";
  } else if (idade >= 18 && idade <= 59) {
    return "Adulto";
  } else {
    return "Sênior";
  }
}

// 5. Atendimento dos pedidos (sem laço de repetição)

// Atendimento do primeiro pedido
let pedido1 = pedidos.shift();
let tipo1 = classificarIngresso(pedido1.idade);
let valor1 = 29.9;
console.log("Cliente atendido:", pedido1.cliente);
console.log("Tipo de ingresso:", tipo1);
console.log("Valor da conta: R$", valor1.toFixed(2));
console.log("Atendimento finalizado");

// Atendimento do segundo pedido
let pedido2 = pedidos.shift();
let tipo2 = classificarIngresso(pedido2.idade);
let valor2 = 29.9;
console.log("Cliente atendido:", pedido2.cliente);
console.log("Tipo de ingresso:", tipo2);
console.log("Valor da conta: R$", valor2.toFixed(2));
console.log("Atendimento finalizado");

// Atendimento do terceiro pedido
let pedido3 = pedidos.shift();
let tipo3 = classificarIngresso(pedido3.idade);
let valor3 = 29.9;
console.log("Cliente atendido:", pedido3.cliente);
console.log("Tipo de ingresso:", tipo3);
console.log("Valor da conta: R$", valor3.toFixed(2));
console.log("Atendimento finalizado");


console.log("Pedidos restantes:", pedidos.shift());
