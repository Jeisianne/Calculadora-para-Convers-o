# Calculadora-para-Conversao
# Converter celsius para fahrenheit e fahrenheit para celsius.

def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32
def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9

print("Escolha a conversão:")
print("1. Celsius para Fahrenheit")
print("2. Fahrenheit para Celsius")

opcao = int(input("digite a opção (1 ou 2): "))

if opcao == 1:
    c = float(input("Digite a temperatura em celsius:  "))
    print(f"{c}°c = {celsius_to_fahrenheit(c):.2f}°f")
elif opcao == 2:
    f= float(input("Digite a temperatura em fahrenheit: "))
    print(f"{f}°f = {fahrenheit_to_celsius(f):.2f}°c")
else:
    print("Opção inválida!")
