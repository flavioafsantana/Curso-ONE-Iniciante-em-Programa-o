# Curso ONE Iniciante em Programação

Desafios: Hora da prática

Desafios

Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```ruby
contador =1;
while(contador <= 10){
    alert(contador);
    contador++;
}
```

Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.

```ruby
contador = 10;
while(contador >= 0){
    alert(contador);
    contador--;
}
```

Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.

```ruby
contagem = prompt('Digite um numero para iniciar a contagem regressiva');
while (contagem >= 0) {
    console.log(contagem);
    contagem--;
}
```

Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.

```ruby
numero = prompt('Digite ate qual numero deseja que eu conte: ');
contagem = 0;
while (contagem <= numero) {
    console.log(contagem);
    contagem++;
}
```
