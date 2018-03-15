def conta_palavras(texto):
    frase = input("Digite um texto: \n")
    return{palavras:frase.count(palavras) for palavras in frase.split(' ')}
    
print(conta_palavras("Venha"))
