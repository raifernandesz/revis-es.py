nome = input("escreva seu nome")
idade = int(input("escreva sua idade"))
if idade>= 18:
    print("acesso liberado")
else:
    print("acesso não liberado")



    nome = input("escreva seu nome")
nota = float(input("escreva sua nota"))
if nota>= 9.0 and nota <= 10.0: 
    print("excelente")
elif nota>= 7.0 and nota <= 8.9: 
    print("bom")
elif nota>= 5.0 and nota <= 6.9:
    print("regular")
elif nota>= 3.0 and nota <=  4.9:
    print("ruim")
elif nota>= 0.0 and nota <= 2.9:
    print("critico")
else:
    print("nota invalida")






nome = input("escreva seu nome")
nivel = float(input("escreva seu nivel"))
if nivel<= 19: 
    print("exausto")
elif nivel>= 20 and nivel <=39: 
    print("cansado")
elif nivel>=  40 and nivel <=59:
    print("neutro")
elif nivel>= 60 and nivel <=79:
    print("animado")
elif nivel>=80 and nivel<= 100:
    print("euforico")
else:
    print("energia invalida")
