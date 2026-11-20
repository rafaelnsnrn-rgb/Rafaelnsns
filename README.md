import random

numero_secreto = random.randint(1, 10)
print("=== JOGO DA ADIVINHAÇÃO ===")
print("Tente adivinhar o número que pensei entre 1 e 10!")

palpite = int(input("Digite seu palpite: "))

if palpite == numero_secreto:
    print(f"Parabéns! Você acertou, o número era {numero_secreto}!")
else:
    print(f"Não foi dessa vez! Eu pensei no número {numero_secreto}.")
