def f(n):
    numerals = [
        {'l': 'M', 'v': 1000},
        {'l': 'D', 'v': 500},
        {'l': 'C', 'v': 100},
        {'l': 'L', 'v': 50},
        {'l': 'X', 'v': 10},
        {'l': 'V', 'v': 5},
        {'l': 'I', 'v': 1}, ]
    dct = {}
    for i in range(len(numerals)):
        dct[numerals[i]['l']] = i
    r = 0#десятичное число
    pv = None #предыдущее значение
    for l in reversed(n):
        i = dct[l]
        v = numerals[i]['v']
        if (pv is None) or (pv <= v):
            r += v
        else:
            r -= v
        pv = v

    return r
print("Десятичное значение числа MDXCXI: ",f( "MDXCXI"))
print("Десятичное значение числа DII: ",f( "DII"))
print("Десятичное значение числа VXLXV: ",f( "VXLXV"))
