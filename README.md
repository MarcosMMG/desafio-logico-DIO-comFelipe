# desafio-logico-DIO-comFelipe

## 1️⃣ Desafio Classificador de nível de Herói

**O Que deve ser utilizado**

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

### Objetivo

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 6.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000= Imortal
Se XP for maior ou igual a 10.001 = Radiante

### Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"

# O codigo 

let nomeChamp = prompt("Digite o nome do herói:");
let xpChamp = prompt("Digite a quantidade de XP do herói:");
let nivelChamp;

if (xpChamp < 1000) {
    nivelChamp = "Ferro"
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 2000) {
    nivelChamp = "Bronze";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 5000) {
    nivelChamp = "Prata";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 6000) {
    nivelChamp = "null";
    console.log("Atenção: A faixa de 5001 a 6000 não contém uma classificação específica. Professor FELIPÂO nao passou os parametros no desafio");
} else if (xpChamp <= 7000) {
    nivelChamp = "Ouro";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 8000) {
    nivelChamp = "Platina";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 9000) {
    nivelChamp = "Ascendente";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else if (xpChamp <= 10000) {
    nivelChamp = "Imortal";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
} else {
    nivelChamp = "Radiante";
    console.log("Olá, " + nomeChamp + " você está no nível de " + nivelChamp + "!");
}



_________________________________--

