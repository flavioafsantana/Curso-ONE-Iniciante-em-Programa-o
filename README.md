# Curso ONE Iniciante em Programação

Desafios: Hora da prática

Desafios

1.Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```ruby
let diaDaSemana = prompt('Qual o dia da semana?');
if (diaDaSemana == 'Sábado'){
    alert('Bom fim de semana!');
} else if (diaDaSemana == 'Domingo'){
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}
```

2.Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```ruby
let numero = prompt('Digite um numero');
if (numero > 0) {
    alert('O numero digitado é positivo');
} else if (numero < 0) {
    alert('O numero digitado é negativo');
} else {
    alert('O numero digitado é zero');
}
```

3.Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".

```ruby
let pontuacao 
if (pontuacao >= 100) {
    console.log('Parabéns, você venceu!');
} else {
    console.log('Tente novamente para ganhar.');
}
```

4.Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```ruby
let saldo = 10;
let mensagem = alert(`Seu saldo é de R$ ${saldo}`);
```

5.Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```ruby
let nome = prompt('Digite seu nome:');
alert(`Olá, ${nome}! Seja bem-vindo!`);
```

