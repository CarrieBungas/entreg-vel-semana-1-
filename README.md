# entregavel-semana-1




Calculadora de troco:

valor_compra = float(input("Digite o valor da compra: "))
valor_pago = float(input("Digite o valor pago: "))

troco = valor_pago - valor_compra

print(f"Troco: R$ {troco:.2f}")






Média de Notas:

nota_1 = float(input("Digite a primeira nota: "))
nota_2 = float(input("Digite a segunda nota: "))
nota_3 = float(input("Digite a terceira nota: "))

media = (nota_1 + nota_2 + nota_3) / 3

print(f"Média: {media:.2f}")







Conversor de tempo:

segundos = int(input("Digite o tempo em segundos: "))

horas = segundos // 3600
minutos = (segundos % 3600) // 60
segundos_restantes = segundos % 60

print(f"{horas} hora(s), {minutos} minuto(s) e {segundos_restantes} segundo(s)")









Calculadora de Desconto:

preco = float(input("Digite o preço do produto: "))
percentual_desconto = float(input("Digite o percentual de desconto: "))

desconto = preco * (percentual_desconto / 100)
preco_final = preco - desconto

print(f"Preço final: R$ {preco_final:.2f}")







Par ou Ímpar:

numero = int(input("Digite um número inteiro: "))

if numero % 2 == 0:
    print(f"{numero} é par")
else:
    print(f"{numero} é ímpar")










Inversor de nome:

nome = input("Digite seu nome: ")

nome_invertido = nome[::-1]

print(f"Nome invertido: {nome_invertido}")





