fator = 1
contador = 0
taxa = eval (input("Digite a taxa de juros anual em porcentagem: "))
while fator < 1.5:
    fator += fator*taxa/100
    contador += 1
print (f"São necessários {contador} anos para atingir 50% de rentabilidade com a taxa de {taxa}% ao ano.")
