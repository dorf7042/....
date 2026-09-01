"""a=int(input("Введите первое число:"))
b=int(input("Введите второе число:"))
print (a/b)
print ("найс")"""
try:
    a=int(input("Fiwe"))
    b=int(input("Fuwe"))
    print (a/b)
except ValueError:
    print("Нельзя вводить строки при делении")
except ZeroDivisionError:
    print("Нельзя делить на ноль")

