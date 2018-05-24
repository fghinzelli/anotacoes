## Forte

 As expressões são avaliadas e não é feita uma conversão automática de tipos incompatíveis.
 Caso seja feita uma tentativa de operação entre tipos incompatíveis, uma exceção será disparada.
 Exemplos: *Python, Java*

## Fraca

 Linguagens com tipagem fraca permitem operações entre tipos inconpatíveis (Ex.: números e textos).
 Exemplos: Javascript.
 
```javascript 
// Exemplo em Javascript
var texto = 'Fernando';
var numero = 10;
console.log(texto + número);
# Será exibido o 'Fernando10'
```

## Estática
 Na definição da variável, o tipo deve ser explicíto. Exemplos: *C, C++, Java*
 
 ```c
 // Exemplo em C
 int main() {
     int a = 10, b = 20;
     printf('O resultado é %d\n', a+b);
 }
 ```

## Dinâmica
 Não é necessário informar o tipo das variáveis, dado que a linguagem infere o tipo pelo valor atribuído. Exemplo: *Python*
 
```python 
# Exemplo em Python
texto = 'Abacaxi'
numero = 12345
texto = numero
# Não haverá erro, pois a variável texto receberá agora passará a ser um int
