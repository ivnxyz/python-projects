# Proyectos en Python
Aquí encontrarás una pequeña lista de proyectos para iniciar a programar en Python.
Si necesitas recordar algunos comandos del lenguaje puedes ir a [Python-101](https://github.com/ivnxyz/python-101).

# Empezando
Puedes usar algún editor de texto como Atom o Sublime Text para escribir tu código y después ejecutarlo en la línea de comandos de tu sistema operativo. De manera alternativa puedes usar un entorno de desarrollo como Thonny, también es recomendable usar Python 3 (la versión por defecto en Thonny).

# Lista de Proyectos
##### Los proyectos NO están ordenados por dificultad.
* [Fizz-Buzz](#fizz-buzz)
* [Números menores a 10](#números-menores-a-10)
* [Extremos de una lista](#extremos-de-una-lista)
* [Lista de elementos compartidos](#lista-de-elementos-compartidos)
* [Palíndromos](#palíndromos)
* [Divisores](#divisores)
* [Cifrado](#cifrado)
* [Bola 8 mágica](#bola-8-mágica)

# Proyectos
### Fizz-Buzz
- Crea un programa que itere una lista de 100 elementos, imprima Fizz para los números divisibles entre 3, Buzz para los números divisibles entre 5 y Fizz-Buzz para los números divisibles entre 5 y 3.
- No escribas la lista manualmente.
### Números menores a 10
- Crea una función que reciba una lista, itere esa lista y DEVUELVA UNA NUEVA LISTA con los elementos menores a 10 de la lista que recibió como parámetro.
- El programa debe estar dentro de una función.
- Tienes que devolver una lista y NO sólo imprimir los números menores a 10.
### Extremos de una lista
- Crea una función que reciba una lista y devuelva una nueva lista con los elementos en los extremos de la lista que recibió como parámetro (el primero y el último).
- Trata de hacerlo en el menor número de líneas posibles.
### Lista de elementos compartidos
- Crea una función que reciba dos listas y devuelva una nueva lista con los elementos que ambas listas tienen en común.
- Trata de hacer que los elementos no se repitan.
### Palíndromos
- Crea una función que reciba un String (una frase) y determine si es un palíndromo (una frase que se lee igual al derecho y al revés).
- Trata de evitar el uso de ciclos for.
### Divisores
- Crea una función que reciba un número y regrese una lista de los divisores de ese número.
- Itera desde 1 hasta el número.
### Cifrado
- Escribe un programa que pueda cifrar y descifrar frases. Debe estar formado de dos funciones, una que reciba una frase para cifrarla y otra que reciba la frase para decifrarla.
- Permite que el usuario ingrese el comando que quiere ejecutar (descifrar o cifrar).
- Permite que el usuario ejecute otro comando o salga del programa.

Pista: usa un diccionario para relacinar una letra con otra.
```python
KEYS = {
    'a': 'w',
    'b': 'E',
    'c': 'x',
    'd': '1',
    'e': 'a',
    'f': 't',
    'g': '0',
    'h': 'C',
    'i': 'b',
    'j': '!',
    'k': 'z',
    'l': '8',
    'm': 'M',
    'n': 'I',
    'o': 'd',
    'p': '.',
    'q': 'U',
    'r': 'Y',
    's': 'i',
    't': '3',
    'u': ',',
    'v': 'J',
    'w': 'N',
    'x': 'f',
    'y': 'm',
    'z': 'W',
    'A': 'G',
    'B': 'S',
    'C': 'j',
    'D': 'n',
    'E': 's',
    'F': 'Q',
    'G': 'o',
    'H': 'e',
    'I': 'u',
    'J': 'g',
    'K': '2',
    'L': '9',
    'M': 'A',
    'N': '5',
    'O': '4',
    'P': '?',
    'Q': 'c',
    'R': 'r',
    'S': 'O',
    'T': 'P',
    'U': 'h',
    'V': '6',
    'W': 'q',
    'X': 'H',
    'Y': 'R',
    'Z': 'l',
    '0': 'k',
    '1': '7',
    '2': 'X',
    '3': 'L',
    '4': 'p',
    '5': 'v',
    '6': 'T',
    '7': 'V',
    '8': 'y',
    '9': 'K',
    '.': 'Z',
    ',': 'D',
    '?': 'F',
    '!': 'B',
}
```
### Bola 8 mágica
- Escribe un programa que reciba una pregunta del usuario y devuelva una respuesta aleatoria.
- Permite que el usuario escriba una pregunta.
- Muestra un mensaje de progreso (por ejemplo: 'pensando...')
- Permite que el usuario haga otra pregunta o salga del programa.

Pista: usa el la función randint(min, max) del módulo random.
```python
import random
```