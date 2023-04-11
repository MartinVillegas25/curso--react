#conceptos de las pruebas unitarias e integrales

# QUE SON LAS PRUEBAS

- DOS TIPOS:
 UNITARIAS:  prueba a un elemento en particular, a una parte del codigo
 INTEGRADORAS: prueba a un conjunto de elementos, relacionados entre ellos.

 - CARACTERISTAS:
  *faciles de escribir
  *faciles de leer 
  *confiables
  *rapidas
  *principalemente unitarias

  # AAA
  A - Arrange (arreglar)
  A- Act (actuar)
  A- Assert (Afirmar)

-
Arrange:
 establecemos el estado inicial
 - inicializamos variables
 - importaciones necesarias -

 Act:
 aplicamos acciones o estimulos al sujeto de pruebas
  - llamamos metodos
  - simular clicks
  - realizar acciones sobre el paso anterior

Assert:
0bservar el comportamiento resultante
 - son los resultados esperados -

 
 # configuraciones de vite para testing

 npm install --save-dev jest
  "scripts": {
    "test": "jest"
  }

  instalar npm add --D @types/jest para las ayuda de jest



para que soporte codigo moderno de JS
  npm install --save-dev babel-jest @babel/core @babel/preset-env 