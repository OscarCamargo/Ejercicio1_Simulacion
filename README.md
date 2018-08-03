# Ejercicio1_Simulación
print("HW 1 Exercise 1")
a=0.5
r=0.5
n=1000
suma = 0
valorfinal=0
thisList = []
for i in range (0,n):
    total=a*(r**i)
    thisList.append(total)
    valorfinal=valorfinal+total
print(thisList)
print(valorfinal)

# No se puede concluir a que número converge para |r|<1 pues al calcular los resultados cambiando r por valores entre 0.1 y 0.9 la serie toma valores diferentes alejados entre sí. Sim embargo, la serie no diverge con |r|<1.
