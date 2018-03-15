def conta_palavras(texto):
    lista = texto.split(' ')
    return{palavras:lista.count(palavras) for palavras in texto.split(' ')}
    
print(conta_palavras("olha o sapo dentro do saco o saco com o sapo dentro o sapo batendo papo e o papo soltando o vento"))
