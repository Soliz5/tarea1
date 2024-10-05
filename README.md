def generar_serie_1(N):
    serie = []
    valor = 1
    for i in range(N):
        serie.append(valor)
        if i % 2 == 0:  
            valor += 4
        else:  
            valor += 2
    return serie
