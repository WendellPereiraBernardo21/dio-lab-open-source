menu = """

{d} Depositar
{s} Sacar
{e} Extrato
{q} Sair


=> """

saldo = 0
limite = 500
extrato = ""
numero_saques = 0
LIMITE_SAQUES = 3

while True:
     
     opcao = input(menu)

     if opcao ==  "d" :
          valor =float(input("Depositar: "))
           
    
        
        
     elif opcao == "s" :
          print ("Sacar")

     elif opcao == "e":
          print("Extrato")

      
     elif opcao == "q":
          print("break")

     else: 
           print("Operação invalida, por favor selecione novamente a operação desejada.")
