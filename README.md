![Ejercicios en C++](            https://www.softzone.es/app/uploads-softzone.es/2022/04/Programacion-C-Cplusplus-csharp.jpg?x=480&y=375&quality=40) 
### Programas en c++ de Girón Genesis
## Informacion del Autor 

`Autor: Genesis Paulina Giron Lupu`

`Correo: genesis.giron.lupu@utelvt.edu.ec`

### Programas 
## Funcionalidad para todos los programas 
 utilizamos las librerias para generar operaciones de entrada/salida. Ademas utilizamos "using namespace" debido que  sirve para distinguir entre funciones que puedan llegar a tener un nombre similar en dos bibliotecas diferentes.

`#include<iostream>`

`using namespace std;`

`int main ()`

## Declaracion de variables

En muchas ocaciones declararemos variables con "int" "float".

Float: utilizamos para declarar una variable de tipo decimal o coma flotante.

Int: utilizamos para almacenan números enteros.

## Compara de dos numeros 

### Descripcion del programa 
Este programa en c++ permite comparar dos numeros y determinar si son igual o cual es el mayor.
### Funcionalidad 
Despues de la explicacion que obtuvimos al inicio para cada uno de los programas.Seguimos con:

`#include<iostream>`

`using namespace std;`

`int main ()`

2.  El segundo paso debemos declarar las variables.

`float GG_A,GG_B;`// Utilizamos float para declarar una variable de tipo decimal o coma flotante.

3. Debemos pedir al usuario que ingrese y lea "GG_A" "GG_B"

`cout<<" ingrese GG_A: "; `

 `cin>>GG_A;`

 
 `cout<<" ingrese GG_B: ";`
 
 `cin>>GG_B;`
 
 4. Realizamos el proceso.
 
 `if(GG_A==GG_B){`
 
`cout<<"el valor de GG_A="<< GG_A<<" es igual a GG_B  "<<GG_B<<endl;`

5. Proceso de salida.
 
 La instrucción return provoca que la ejecución abandone la función main.
 
`return 0;`

## Suma de varios numeros

### Descripcion del programa 
Este programa en c++ permite sumar varios numeros  donde el contador debe ser menor que la cantidad de números ingresados, para luego calcular la suma de cada número ingresado por teclado.

### Funcionalidad 


## Calcula la edad
### Descripcion del programa
Este programa en c++ permite calcular la edad de una persona a partir del año actual y su fecha de nacimiento. 
### Funcionalidad 

## Punto de venta
### Descripcion del programa 
Este programa en c++ permite ingresar la cantidad de los productos a adquirir incluyendo iva y descuento. 
### Funcionalidad 

## Cuenta moneda
### Descripcion del programa 
Este programa c++ permite ingresar el numero de monedas, para luego contar la cantidad de monedas que fueron ingresadas, tanto de 0.10 ctvs y 0.25 ctvs   y asi obtener la cantidad de monedas que fueron contadas.
### Funcionalidad 

## Instalacion 
### Descargar el repositorio 

1. Clonar el repositorio de la maquina local.
```
git clone https://github.com/Josselyn-Banguera/ProgramacionGrupo.git
```
2. Ingresar a la carpeta con el comando cd 
```
cd GironGenesis 
```
### Copilar y ejecutar 
```
g++ GironGenesis-Compara.cpp -o GironGenesis-Compara 
```
```
./GironGenesis-Compara 
```
