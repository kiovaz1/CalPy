import math

while True:
    numero_1 = input('Insira o primeiro número: \n')
    numero_2 = input('Insira o segundo número: \n')
    operador = input('Digite o operador (+ - / *): \n')

    try:
        num_1_float = float(numero_1)
        num_2_float = float(numero_2)
    except ValueError:
        print('Você digitou um ou dois números inválidos.')
        continue

    if operador not in '+ - / *':
        print('Operador inválido.')
        continue

    if operador == '+':
        resultado = num_1_float + num_2_float
    elif operador == '-':
        resultado = num_1_float - num_2_float
    elif operador == '*':
        resultado = num_1_float * num_2_float
    elif operador == '/':
        resultado = num_1_float / num_2_float if num_2_float != 0 else math.inf # infinito positivo

    print(f'O resultado é: {resultado}')

    sair = input('Quer sair? [s]im: \n').lower().startswith('s')
    if sair:
        break
