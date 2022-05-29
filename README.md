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
1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`

2. Declaramos las variables.

`int GG_c= 0, GG_n;`

`float GG_s=0, GG_x;`

3. Pedimos al usuario que lea y ingrese el valor de la suma.

`cout<<"Ingrese la cantidad de valor a suma : ";`

`cin>>GG_n;`

4. Realizamos el proceso.

Utilizaremos la sentencia do-while se utiliza para especificar un ciclo condicional que se ejecuta al menos una vez.

`do{ `

`cout<<"Ingrese el elemento: ";`

 `cin>>GG_x;`
 
 `GG_c=GG_c+1;`
 
 `GG_s=GG_s+GG_x;`
 
 `}while (GG_c<GG_n);`
 
 5. Proceso de salida.
 
 La instrucción return provoca que la ejecución abandone la función main.
 
`return 0;`
 
## Calcula la edad

### Descripcion del programa
Este programa en c++ permite calcular la edad de una persona a partir del año actual y su fecha de nacimiento. 

### Funcionalidad 

1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`

2. Declaramos las variables en la que vamos a almacenar los datos.

`int GG_da,GG_ma,GG_aa,GG_dn,GG_mn,GG_an,GG_a,GG_m,GG_d;`

3. Pedimos al usuario que lea y ingrese la fecha actual y la fecha de nacimiento.

`cout<<"Ingrese la fecha actual: Dia Mes Año :";`

`	cin>>GG_da>>GG_ma>>GG_aa;`
 
`cout<<"Ingrese su fecha de nacimiento: Dia Mes Año :";`

`	cin>>GG_dn>>GG_mn>>GG_an;`

4. Realizamos el proceso.
Pero en este caso usaremos los condicionales if-else,son una estructura de control, que nos permiten tomar cierta decisión al interior de nuestro algoritmo, es decir, nos permiten determinar que acciones tomar dada o no cierta condició

`if(GG_da>=GG_dn){`

`GG_d=GG_da-GG_dn;`
  
`	}`
 
 `else{`
  
 `GG_da=GG_da+30;`
		
 `GG_ma=GG_ma-1;`
         
 `GG_d=GG_da-GG_dn;`
	


## Punto de venta

### Descripcion del programa 
Este programa en c++ permite ingresar la cantidad de los productos a adquirir incluyendo iva y descuento.

### Funcionalidad 

1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`


## Cuenta moneda

### Descripcion del programa 

Este programa c++ permite ingresar el numero de monedas, para luego contar la cantidad de monedas que fueron ingresadas, tanto de 0.10 ctvs y 0.25 ctvs   y asi obtener la cantidad de monedas que fueron contadas.

### Funcionalidad 

1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`


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
