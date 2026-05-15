# meu-projeto
n1 = int(input("Insira um número inteiro:"))
n2 = int(input("Insira um segundo número inteiro:"))
operador = input("Voçê deseja adicionar, subtrair, multiplicar ou dividir esses números?")
def calcular(n1,n2,operador):

 if operador == "adicionar":
  return n1 +n2
 elif operador == "subtrair":
  return n1 - n2
 elif operador == "multiplicar":
  return n1 * n2
 elif operador == "dividir":
  return n1 / n2
 else:
  return "Operação inválida!"

resultado = calcular(n1,n2,operador)
print(f"Seu resultado é : {resultado}")
