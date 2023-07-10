**Faça uma função calculadora que os números e as operações serão feitas pelo usuário. O código deve ficar rodando infinitamente até que o usuário escolha a opção de sair. No início, o programa mostrará a seguinte lista de operações:

1: Soma
2: Subtração
3: Multiplicação
4: Divisão
0: Sair

Digite o número para a operação correspondente e caso o usuário introduza qualquer outro, o sistema deve mostrar a mensagem “Essa opção não existe” e voltar ao menu de opções.

Após a seleção, o sistema deve pedir para o usuário inserir o primeiro e segundo valor, um de cada. Depois precisa executar a operação e mostrar o resultado na tela. Quando o usuário escolher a opção “Sair”, o sistema irá parar.

É necessário que o sistema mostre as opções sempre que finalizar uma operação e mostrar o resultado. 

Resposta: **

def calculadora(1num, 2num, operacao):
if (operacao ==1):
return 1num + 2num
elif (operacao ==2):
return 1num - 2num
elif (operacao ==3):
return  1num * 2num
elif (operacao ==4):
return 1num / 2num
else: 
return 0

executar = True

while (executar == True): 
print("Qual conta você deseja realizar?")
print("1: Soma 2: Subtração 3: Multiplicação 4: Divisão 0: Sair")
operacao = int(input())
if(operacao < 0) or (operacao > 4):
print("Essa opção não existe")
elif(operacao == 0):
executar = False
else: 
print("Insira o primeiro número da operação:")
1num = int(input())
print("Insira o segundo número da operação:")
2num = int(input())
resultado = calculadora (num1, 2num, operacao)
print("O resultado é:", resultado)
