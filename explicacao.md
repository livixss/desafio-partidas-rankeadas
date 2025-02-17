Instruções para entrega
 # 2️⃣ Calculadora de partidas Rankeadas
**O Que deve ser utilizado**

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões
- Funções

## Objetivo:

Crie uma função que recebe como parâmetro a quantidade de vitórias e derrotas de um jogador,
depois disso retorne o resultado para uma variável, o saldo de Rankeadas deve ser feito através do calculo (vitórias - derrotas)

Se vitórias for menor do que 10 = Ferro
Se vitórias for entre 11 e 20 = Bronze
Se vitórias for entre 21 e 50 = Prata
Se vitórias for entre 51 e 80 = Ouro
Se vitórias for entre 81 e 90 = Diamante
Se vitórias for entre 91 e 100= Lendário
Se vitórias for maior ou igual a 101 = Imortal

## Saída

Ao final deve se exibir uma mensagem:
"O Herói tem de saldo de **{saldoVitorias}** está no nível de **{nivel}**"
 


 switch (){
    case " vitorias > 10":
    console.log("Você eh da familia, pode entrar!");
    break; 
    case "LaraF":
    console.log("Você eh da familia, pode entrar!");
    break;
    case "Lucas":
    console.log("Você eh da familia, pode entrar!");
    break;
    case "Livia":
    console.log("Você eh da familia, pode entrar!");
    break;
    
    default:
    console.log("Você não eh da familia, saia")
}


let saldoVitorias = vitorias > 10 (calculoDePartidas)
console.log("O Herói tem de saldo de "+ saldoVitorias + está no nível de )


function calculoDePartidas (vitorias, derrotas){
    let resultado = (vitorias - derrotas)
    return resultado
}