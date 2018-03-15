def conta_palavras(texto):
    return{palavras:texto.count(palavras) for palavras in texto.split(' ')}
    
print(conta_palavras("três pratos de trigo para três tigres tristes"))
