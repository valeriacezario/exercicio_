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

def calculadora(1soma, 2subtracao, 3multiplicacao, 4divisao, 0sair, operacao) 
if (operacao ==1):
return 1soma
elif (operacao ==2):
return 2subtracao
elif (operacao ==3):
return 3multiplicacao
elif (operacao ==4): 
return 4divisao
elif (operacao ==0):
else return 0sair
else:
print('Essa opção não existe!')
return (1soma, 2subtracao, 3multiplicacao, 4divisao, 0sair, operacao)


