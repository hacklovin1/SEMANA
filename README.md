# SEMANA
#semana.py
cadenaPalabras = '''XXXXXXXXX'''

listaPalabras = cadenaPalabras.split()

frecuenciaPalab = []
for w in listaPalabras:
	frecuenciaPalab.append(listaPalabras.count(w))
	
print("Cadena\n" + cadenaPalabras +"\n")
print("Lista\n" + str(listaPalabras) +"\n")
print("Frecuencias\n" + str(frecuenciaPalab) +"\n")
print("Pares\n" + str(list(zip(listaPalabras, frecuenciaPalab))))
