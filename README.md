  Olá pessoal! Aqui venho compartilhar a minha primeira atividade do curso que venho estudando,
que é basicamente alterar a mensagem de alert para adicionar o número que o usuário errou no final do resultado.

alert('Bem-vindo ao jogo do número secreto')
let chute = prompt('Escolha um número entre 1 e 10')

let numeroSecreto = 4

console.log(chute == numeroSecreto)
if (chute == numeroSecreto) {
    alert('Acertou')
} else {
    alert('O número secreto era ' + numeroSecreto, 'mas voce escolheu' + chute)
