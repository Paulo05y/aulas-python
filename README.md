# aulas-python

![image](https://github.com/user-attachments/assets/2a73040a-4801-4e27-916b-93111d915b5b)


## tipos primitivos: string, number(int/float), boolean

Para saber mais, <br/> [Clique aqui.](https://www.alura.com.br/artigos/python?srsltid=AfmBOoob9Gzfni1enJi4UgXV0typmUAWUl3zNkFw35sYAeJOOKIk-gqp)

### Operadores aritmérticos
#### Operadores lógicos/comparativos
- **Estruturas** **_condicionais_** (if/elif/else)

- **Tipos de estruturas condicionais:**

- if: Executa um bloco do código se uma condição especificada for verdadeira.
- elif: Significa "else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

```py
tereza = 1.80
marcelo = 1.80

#Se for positivo, o print será ativado
if marcelo > tereza:
  print("Marcelo é mais alto")
elif marcelo == tereza:
  print("Marcelo é Tereza")
else:
  print("Tereza é mais alta")
