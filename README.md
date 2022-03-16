# ExtWrk

#1.Pedir nome e utiliza-lo em toda seguinte comunicação
#2.Pratos
#3.Pizza; sabor e complemento / Macarrão; massa e molho
#4.Mensagem informando o pedido do cliente



print("\nAtendente\n\tOlá seja bem vindo(a) à Massas.com, como podemos te chamar?")
clientName = input("\nInsert your name...\n\t")

print("\nAtendente\n\tÓtimo", clientName, ", e o que deseja? Pizza ou Macarrão?")
print("\nInsert an option from below...\n\t1.Pizza\n\t2.Macarrão")
clientRequest = ("\nPedido.:\n")

clientOption = int(input())
if clientOption == 1:
    clientRequest = clientRequest + ("Pizza")
    print("\n", clientName, "\n\tEu gostaria de uma pizza.")
    print("\nAtendente\n\tPizza salgada ou doce?")
    print("\nInsert an option from below\n\t1.Salgada\n\t2.Doce")
    
    clientOption_Pizza = int(input())
    if clientOption_Pizza == 1:
        clientRequest = clientRequest + (" salgada")
        print("\nAtendente\n\tÓtima escolha, e qual sabor do cardápio?")
        print("\nInsert an option from below\n\t1.Marguerita\n\t2.Champgnom\n\t3.Calabresa")
        
        clientOption_PizzaS = int(input())
        if clientOption_PizzaS == 1:
            clientRequest = clientRequest + (" marguerita")
            print("\n", clientName, "\n\tA de sempre, marguerita")
            print("\nAtendente\n\tCom manjeiricão?")
            print("\nInsert an option from below\n\t1.Sim\n\t2.Não")
            
            clientOption_PizzaSM = int(input())
            if clientOption_PizzaSM == 1:
                clientRequest = clientRequest + (" com manjericão")
                print("\n", clientName, "\n\tSim")
                print("\nAtendente\n\tUma margutia com manjericão saíndo!")
                print("\n - - - - - - - - - -\nCliente de n° 101\n\t", clientName, clientRequest)
            
            elif clientOption_PizzaSM == 2:
                clientRequest = clientRequest + (" sem manjericão")
                print("\n", clientName, "\n\tSim")
                print("\nAtendente\n\tUma margutia sem manjerição saíndo!")
                print("\n - - - - - - - - - -\nCliente de n° 102\n\t", clientName, clientRequest)
            
            else:
                print("Something went wrong, can you repeat?")
                clientOption_PizzaSM = int(input())

        elif clientOption_PizzaS == 2:
            clientRequest = clientRequest + (" champgnom")
            print("\n", clientName, "\n\tUma de cogumelos, por favor.")
            print("\nAtendente\n\tUma pizza de cogumelo saíndo! Ops, uma de champgnom saíndo!")
            print("\n - - - - - - - - - -\nCliente de n° 103\n\t", clientName, clientRequest)
        
        elif clientOption_PizzaS == 3:
            clientRequest = clientRequest + (" calabresa")
            print("\n", clientName, "\n\tDesta vez uma calabreza")
            print("\n Atendente\n\tUma pizza de calabreza saíndo!")
            print("\n - - - - - - - - - -\nCliente de n°104\n\t", clientName, clientRequest)
            
        
    elif clientOption_Pizza == 2:
        clientRequest = clientRequest + (" doce")
        print("\nAtendente\n\tÓtimo, e qual sabor do cardápio?")
        print("\nInsert an option from below...\n\t1.Prestígio\n\t2.Banana\n\t3.M&m")
      
        clientOption_PizzaD = int(input())
        if clientOption_PizzaD == 1:
            clientRequest = clientRequest + (" prestígio")
            print("\n",clientName, "Uma de prestígio.")
            print("\nAtendente\n\tBeleza, uma prestígio saíndo!")
            print("\n - - - - - - - - - -\nClient de n°105\n\t", clientName, clientRequest)
          
        elif clientOption112 == 2:
            clientRequest = clientRequest + (" banana")
            print("\n", clientName, "Uma de bananas.")
            print("\nAtendente\n\tOk ok, uma pizza de banana saíndo!")
            print("\n - - - - - - - - - -\n\tClient de n°106\n\t", clientName, clientRequest)

        elif clientOption112 == 3:
            clientRequest = clientRequest + (" M&m")
            print("\n", clientName, "Uma de M&m")
            print("\nAtendente\n\tòtimo, uma pizza de M&ms saíndo!")
            print("\\n - - - - - - - - - -\n\tCliente de n°107\n\t", clientName, clientRequest)
                
    else:
            print("Something went wrong, can you repeat?")
            clientOption11 = int(input())

elif clientOption == 2:
    clientRequest = clientRequest + ("Macarrão")
    print("\n", clientName, "\n\tEu gostaria de uma macarronada.")
    print("\nAtendente\n\tE que molho gostaria?")
    print("\nInsert an option from below\n\t1.Vermelho\n\t2.Branco")
    
    clientOption_Macarrão = int(input())
    if clientOption_Macarrão == 1:
        clientRequest = clientRequest + (", molho vermelho")
        print("\n", clientName, "\n\nCom molho vermelho")
        print("\nAtendente\n\tÓtimo, e gostaria de orégano, queijo ralado ou os dois?")
        print("\nInsert an option from below\n\t1.Orégano\n\t2.Quejo-Ralado\n\t3.Orégano e queijo ralado\n\t4.Nada")

        clientOption_MacarrãoVComp = int(input())
        if clientOption_MacarrãoVComp == 1:
            clientRequest = clientRequest + (" com orégano")
            print("\n", clientName, "\n\tOrégano, por favor.")
            print("\nAtendente\n\tBeleza, uma macarronada com orégano saíndo!")
            print("\n - - - - - - - - - -\n\tCliente de n°108\n\t", clientName, clientRequest)
        
        elif clientOption_MacarrãoVComp == 2:
            clientRequest = clientRequest + (" com queijo ralado")
            print("\n", clientName, "\n\tQueijo ralado, por favor.")
            print("\nAtendente\n\tBeleza, uma macarronada com queijo ralado saíndo!")
            print("\n - - - - - - - - - -\n\tCliente de n°109\n\t", clientName, clientRequest)

        elif clientOption_MacarrãoVComp == 3:
            clientRequest = clientRequest + (" com orégano e queijo-ralado")
            print("\n", clientName, "\n\tOs dois, por favor")
            print("\nAtendente\n\tÓtimo, uma macarronada com orégano e queijo ralado saíndo!")
            print("\n - - - - - - - - - -\n\tCliente de n°110\n\t", clientName, clientRequest)
        
        elif clientOption_MacarrãoVComp == 4:
            clientRequest = clientRequest + (" sem complemento")
            print("\n", clientName, "\n\tSem complemento dessa vêz")
            print("\nAtendente\n\tOk ok, uma macarronada sem complemento saíndo!")
            print("\n - - - - - - - - - -\n\tCliente de n°111\n\t", clientName, clientRequest)

        else:
            print("\nSomenthing went wrong, can you repeat?")
            clientOption_MaccarãoVComp = int(input())

    elif clientOption_Macarrão == 2:
        clientRequest = clientRequest + (", molho branco")
        print("\n", clientName, "\n\tCom molho vermelho")
        print("\nAtendente\n\tÓtimo, uma macarronada com molho branco saídno!")
        print("\n - - - - - - - - - -\n\tCliente de n°112\n\t", clientName, clientRequest)

else:
    print("something went wrong, can you repeat?")
    clientOption1 = int(input)
