# JogoDosDados
#Projeto Python para executar os comandos de perguntas e fazer uma simulação de dados.

from random import randint

while True:
    pergunta = input("Você gostaria de jogar o dado? ")

    if pergunta == 'sim':
        for x in range (1):
            print(randint(1, 6))
    else:
        print("Fim de Jogo")
    
        break
    


