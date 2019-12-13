print("Введіть 'exit' щоб вийти")
while True:
    s = input("Знак (+,-,*,/): ")
    if s == 'exit': break
    if s in ('+','-','*','/'):
        x = input("x=")
        if (x.isdigit()):
            x = float(x)
        else:
            print("Помилка!")
            break
        y = (input("y="))
        if (y.isdigit()):
            y = float(y)
        else:
            print("Помилка!")
            break
        if s == '+':
            print("%.2f" % (x+y))
        elif s == '-':
            print("%.2f" % (x-y))
        elif s == '*':
            print("%.2f" % (x*y))
        elif s == '/':
            if y != 0:
                print("%.2f" % (x/y))
            else:
                print("Ділення на нуль!")
    else:
        print("Неправельний знак!")
