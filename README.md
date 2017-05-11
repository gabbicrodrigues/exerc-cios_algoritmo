# exerccios_algoritmo
#exercício 15 lista 6_funções 

a=[]
def ordemCresc(a):
	a.sort()
	return a 

for i in range(5):
	print('Digite um',(i+1),'numero: ')
	a.append(float(input()))
x=ordemCresc(a)
print('A ordem é',x)
