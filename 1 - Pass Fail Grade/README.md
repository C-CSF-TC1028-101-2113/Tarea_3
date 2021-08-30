# Pass Fail Grade
Decisiones - Calificacion aprobatoria o reprobatoria

Modifica el siguiente codigo:

```python
def check_grade(grade):
    # escribe tu código abajo de esta línea
    pass


def main():
    grade = int(input("Enter grade: "))
    print(check_grade(grade))


if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario,
el programa la va a ignorar al ejecutarse.

El programa va a preguntar por una calificación numerica, entre 0 y 100.
Añade el código necesario para que el programa imprima **Pass** si la
calificación es mayor o igual a 70, o que imprima **Fail** si la
calificación es menor a 70.

La salida del programa debe de ser exactamente de la siguiente forma:

```plaintext
Enter grade: 90
Pass
```

Elimina la palabra __pass__ y escribe el código necesario.
Asegurarte de que la función regrese la palabra correcta.
