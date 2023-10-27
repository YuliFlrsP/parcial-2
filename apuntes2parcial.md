#     Universidad de Colima 
##    Ingenieria Computacion Inteligente 
###                Apuntes 2 Parcial
#### Yuli Janeth Flores Pascual 


_____________________








def my_function(my_list=[]):
    my_list.append('???')
    return my_list
    
    
    
    
    
    my_function(["a", "b", "c"])

    Returns the average of a list of numeric values.


['a', 'b', 'c', '???']


my_function([1, 2, 3, 4, 5])

#Si se llama sin ningún argumento
print(my_function())
print(my_function())
print(my_function())



#Si se llama sin ningún argumento
print(my_function())
print(my_function())
print(my_function())




def f1():
    print("Hola")
    print("Mundo")
    return

f1()



def f(x):
    if x < 0:
        return
    if x > 10:
        return
    print(x)
    
    
    
    
    def f():
    return


print(f())



def f():
    return

def g():
    pass


if f() or g():
    print('yes')
else:
    print('no')
    
    
    
    
    def f():
    return True

def g():
    pass


if f() or g():
    print('yes')
else:
    print('no')
    
    
    
    
    
     Definir la función double
def double(x:int)->int:
    return x * 2

 Asignar la función double a la variable my_double
my_double = double
print(type(my_double))

 Llamar a la función a través de la variable
result = my_double(5)

 Imprimir el resultado
print(result)



def double(x:int)->int:
    return x * 2

# Llamar a la función a través de la variable
doble = double(3)

def cuad(f):
    return f ** 2

cuadrado = cuad(doble)
print(cuadrado)




def cuad(n:int)->int:
    return n ** 2


def elevar_numeros(lista, cuad):
    lista_cuadrados = []
    for num in lista:
        lista_cuadrados.append(cuad(num))
    return lista_cuadrados


lista = [1, 2, 3, 4, 5]
print(elevar_numeros(lista, cuad))



def cuad(n:int)->int:
    return n ** 2


def elevar_numeros(lista):
    lista_cuadrados = []
    for num in lista:
        lista_cuadrados.append(cuad(num))
    return lista_cuadrados


lista = [1, 2, 3, 4, 5]
print(elevar_numeros(lista))


def suma(a, b):
    """
    This function adds two numbers.

    Parameters:
    a (int): The first number.
    b (int): The second number.

    Returns:
    int: The sum of a and b.
    """
    return a + b

def resta(a, b):
    """
    This function subtracts two numbers.

    Parameters:
    a (int): The first number.
    b (int): The second number.

    Returns:
    int: The difference between a and b.
    """
    return a - b

def multiplicacion(a, b):
    """
    This function multiplies two numbers.

    Parameters:
    a (int): The first number.
    b (int): The second number.

    Returns:
    int: The product of a and b.
    """
    return a * b

def division(a, b):
    """
    This function divides two numbers.

    Parameters:
    a (int): The first number.
    b (int): The second number.

    Returns:
    float: The quotient of a and b.
    """
    return a / b


def suma(a, b):
    """
    This function adds two numbers.

    Parameters:
    a (int): The first number.
    b (int): The second number.

    Returns:
    int: The sum of a and b.
    """
    # Check if both a and b are integers
    if not isinstance(a, int) or not isinstance(b, int):
        print("Both a and b should be integers.")
        return None
    
    # Add a and b
    result = a + b
    
    # Print the result
    print(f"The sum of {a} and {b} is {result}.")
    
    return result

