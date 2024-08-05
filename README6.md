print('+ adição')
print('- subtração')
print('* multiplicação')
print('/ Divisão')
print('** exponiciação')
print('Pressione qualquer tecla para sair')

while True:
    op = input('Digite a operação desejada a seguir')
    if op == '+' or op == '-' or op == '*' or op == '/' or op == '**':
        x = int(input('digite o primeiro valor:'))
        y = int(input('digite o segundo valor:'))

        if op == ('+'):
            res = x + y
            print('Resultado {} + {} = {}'.format(x,y,res))

        elif op == ('-'):
            res = x - y
            print('Resultado {} - {} = {}'. format(x,y,res))

        elif op == ('*'):
            res = x * y
            print('Resultado {} * {} = {}'.format(x,y,res))

        elif op == ('/'):
            res = x / y
            print('Resultado {} / {} = {}'.format(x,y,res))

        elif op == ('**'):
            res = x ** y
            print('Resultado {} ** {} = {}'.format(x,y,res))

        elif(op == "S"):
            break

print('operação invalida')
print('encerrando o programa.............')