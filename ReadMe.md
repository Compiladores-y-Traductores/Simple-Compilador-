# Compilador Simple Con Bison y Flex

## Hecho por Juan Pablo de Jesus Figueroa Jaramillo

### Que es un compilador?

En informática, un compilador es un tipo de traductor que transforma un programa entero de un lenguaje de programación a otro.​ Usualmente el lenguaje objetivo es código máquina, aunque también puede ser traducido a un código intermedio o a texto.

### Estructura

- CG.h
- Simple.lex
- SM.h
- ST.h
- Simple.y

### Como iniciar ?

1. Clona el repositorio de github
2. Crea una rama alterna dentro del repositorio con: 

            git checkout -b nombre_de_tu_rama

3. Dentro de la ruta del proyecto abre la terminal de comandos e ingresa lo siguiente:

            make

4. Para probar el ejecutable tienes que ingresar el siguiente comando:

            make probar

### Comandos del Make

- make: Ejecuta todos los procesos de compilacion y analisis lexico dentro de los documentos.
- clean: Limpia los elementos creados del producto de la compilacion y flexeado.
- probar: Con este lanzamos el comando de prueba.

