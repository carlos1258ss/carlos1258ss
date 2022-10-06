#cadastro de vinho
cadastro = ['pergola', '1950']
outros = ['vinho tinto']
vinho = input("digite o nome do vinho:")
ano = int(input("qual o ano do vinho:"))
vinhos = {vinho, ano} 
cadastro.append([vinhos])
if ano >= 20:
    print ("preço do vinho = 159")
if ano < 20:
    print ("preço do vinho = 69")

cadastro.pop(0)
cadastro.insert(1, 'vinho chileno')

#caso queira unir listas
#for i range (3):
#    tupla = (cadastro [i-1], outros [i-1])

print (cadastro[1:-1])
print (cadastro[1])
print (cadastro)
