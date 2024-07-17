valorDigitado = input('Qual o valor do litro do combustivel (R$): ')  
valor = float(valorDigitado.replace(',' , '.'))
valorDinheiro = input("Qual o valor em dinheiro que deseja abastecer?\n valor (R$): ")
valorDinheiro = float(valorDinheiro.replace(',' , '.'))
quantidadeCombustivel = valorDinheiro / valor
print(f"quantidade em litros: {quantidadeCombustivel}")
