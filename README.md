# homework
print('собака короткошерстной породы?')
otvet=input()
if otvet==('да'):
    print('рост собаки менее 50 см?')
    otvet=input()
    if otvet=='да':
        print('у собаки короткий хвост?')
        otvet=input()
        if otvet=='да':
            print('английский бульдог')
        else:
            print('у собаки длинные уши?')
            otvet=input()
            if otvet=='да':
                print('гочная')
            else:
                print('у собаки короткое тело?')
                otvet=input()
                if otvet=='да':
                    print('мопс')
                else:
                    print('хичуачуа')
    else:
        print('собака весит более 50 кг?')
        otvet=input()
        if otvet=='да':
            print('датский дог')
        else:
            print('фоксхаунт')
else:
    print('рост собаки менее 50 см?')
    otvet=input()
    if otvet=='да':
        print('у собаки доброжелательный характер?')
        if otvet=='да':
            print('кокер-спаниэль')
        else:
            print('ирландский сеттер')
    else:
        print('у собаки рост менее 70 см?')
        otvet=input()
        if otvet=='да':
            print('у собаки длинные уши?')
            otvet=input()
            if otvet=='да':
                print('большой вандейский грифон')
            else:
                print('копли')
        else:
            print('окрас рыжий с белыми отметинами?')
            otvet=input()
            if otvet=='да':
                print ('сербернар')
            else:
                print('белоснежный окрас?')
                otvet=input()
                if otvet=='да':
                    print('ирландский волкодав')
                else:
                    print('ньюфауленд')
