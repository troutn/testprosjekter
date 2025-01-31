import random

stein = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

papir = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

saks = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
print("velkommen til Stein, Saks, Papir spillet!\n ")
spiller_valg = input(' Hva velger du? skriv "stein", "saks" eller "papir"\n ').lower()

motstander = [stein, saks, papir]
motstander_valg = (random.choice(motstander)).lower()

#stein

if spiller_valg == "stein":
    print(stein)
    print(motstander_valg)
    if motstander_valg == saks:
        print("Stein slår Saks. Gratulerer du vinner!")
    elif motstander_valg == papir:
        print("Papir slår Stein. Du tapte!")
    else:
        print("Uavgjort, Prøv igjen!")


elif spiller_valg == "saks":
    print(saks)
    print(motstander_valg)
    if motstander_valg == papir:
        print("Saks slår Papir. Gratulerer du vinner!")
    elif motstander_valg == stein:
        print("Stein slår Saks. Du tapte!")
    else:
        print("Uavgjort, Prøv igjen!")

# Papir

elif spiller_valg == "papir":
    print(papir)
    print(motstander_valg)
    if motstander_valg == stein:
        print("Papir slår Stein. Gratulerer du vinner!")
    elif motstander_valg == saks:
        print("Saks slår Papir. Du tapte!")
    else:
        print("Uavgjort, Prøv igjen!")

