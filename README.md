# 1A-mediotec
import random

caracteres = "abcdefghijklmnopqrstuvyxwzABCDEFGHIJKLMNOPQRSTUVYXWZ0123456789"

quantidade = int(input("Quantos caracteres a senha deve ter? "))

senha = ""

for i in range(quantidade):
  senha += random.choice(caracteres)

print(f"\nSenha gerada: {senha}")