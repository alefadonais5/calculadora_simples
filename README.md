# calculadora_simples
operacao = 0
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

while operacao != 6:

    operacao = float(input("1. para soma: \n"
                           "2. para subtração: \n"
                           "3. para multiplicação: \n"
                           "4. para divisão: \n"
                           "5. para digitar um novo número: "
                           "6. para sair: "))
    while True:

        if operacao == 1:
            print("A soma é igual a: ", num1+num2)

            break
        elif operacao == 2:
            print("A subtração é igual a: ", num1-num2)
            break

        elif operacao == 3:
            print("A multiplicação é igual a: ", num1*num2)
            break

        elif operacao == 4:
            print("A divisão é igual a: ", num1/num2)

        elif operacao == 5:
            num1 = float(input("Digite o primeiro número: "))
            num2 = float(input("Digite o segundo número: "))
            break
        elif operacao == 6:
            print("Programa encerrado.")
            break
    break
