import os
while True:
  x = float(input("escolha um  numero:"))
  op = input("escolha uma operação:")
  y = float(input("escolha outro numero:"))
  if op == "+":
    print(x+y)
  elif op == "-":
    print(x-y)
  elif op == "*":
    print(x*y)
  elif op == "/":
    print(x/y)
  elif op == "^":
    print(x**y)
  else:
    os.system("clear")
    print("erro na matematica")
    
