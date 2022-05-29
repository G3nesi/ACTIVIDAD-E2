![Ejercicios en C++](            https://www.softzone.es/app/uploads-softzone.es/2022/04/Programacion-C-Cplusplus-csharp.jpg?x=480&y=375&quality=40) 
### Programas en c++ de Girón Genesis
## Informacion del Autor 

`Autor: Genesis Paulina Giron Lupu`

`Correo: genesis.giron.lupu@utelvt.edu.ec`

### Programas 
## Funcionalidad para todos los programas 
 Utilizamos las librerias para generar operaciones de entrada/salida. Ademas utilizamos "using namespace" debido que  sirve para distinguir entre funciones que puedan llegar a tener un nombre similar en dos bibliotecas diferentes.

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

Utilizamos float para declarar una variable de tipo decimal o como flotante.

`float GG_A,GG_B;`

3. Debemos pedir al usuario que ingrese y lea "GG_A" "GG_B"

`cout<<" ingrese GG_A: "; `

 `cin>>GG_A;`

 
 `cout<<" ingrese GG_B: ";`
 
 `cin>>GG_B;`
 
 4. Realizamos el proceso.
 
 `if(GG_A==GG_B){`
 
`cout<<"el valor de GG_A="<< GG_A<<" es igual a GG_B  "<<GG_B<<endl;`

5. Mostramos por pantalla.

`cout<<"el valor de GG_A=" <<GG_A<<"es menor a GG_B= "<<GG_B<<endl;`

`}else{`

`cout<<"el valor de GG_B="<<GG_B<<"es menor a  GG_A= "<<GG_A<<endl;`
	}
### Salida.
 
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
 
 5. Mostramos por pantalla.

 `cout<<"La suma de los elementos fue : "<<GG_s<<endl; `
 
 ### Salida.
 
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
Pero en este caso usaremos los condicionales if-else,son una estructura de control, que nos permiten tomar cierta decisión al interior de nuestro algoritmo, es decir, nos permiten determinar que acciones tomar dada o no cierta condición.

`if(GG_da>=GG_dn){`

`GG_d=GG_da-GG_dn;`
  
`	}`
 
 `else{`
  
 `GG_da=GG_da+30;`
		
 `GG_ma=GG_ma-1;`
         
 `GG_d=GG_da-GG_dn;`
 
 5. Mostrar por pantalla.

cout<<"Usted tiene: " <<GG_a<< "años" <<GG_m<< "meses" "y" <<GG_d<< "dias";
	
### Salida.
 
 La instrucción return provoca que la ejecución abandone la función main.
 
`return 0;`

## Punto de venta

### Descripcion del programa 
Este programa en c++ permite ingresar la cantidad de los productos a adquirir incluyendo iva y descuento.

### Funcionalidad 

1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`

2. Declaramos las variables en la que vamos a almacenar los datos.

`int GG_c=0, GG_P;`

`float GG_a=0, GG_x, GG_tb, GG_viva, GG_vdes, GG_iva=0.12, GG_des=0.30, GG_vf;`

3. Pedimos al usuario que lea y ingrese la cantidad de productos.

`cout<<"Ingrese la cantidad de productos: ";`

`cin>>GG_P;`

4. Realizamos el proceso.

Utilizaremos la sentencia do-while se utiliza para especificar un ciclo condicional que se ejecuta al menos una vez.

`do{`

`cout<<"Ingrese el valor de los productos: ";`

`cin>>GG_x;`

`GG_c=GG_c+1;`

`GG_a=GG_a+GG_x;`

`GG_viva=GG_a*GG_iva;`

`cout<<"El valor del iva de la compra es de: $"<<GG_viva<<endl;`

`GG_vdes=GG_a*GG_des;`

`cout<<"El valor del descuento de su compra es de:$"<<GG_vdes<<endl;`

`GG_tb=GG_viva+GG_vdes;`

`}while(GG_c<GG_P);`

5. Mostrar por pantalla.

`cout<<"El valor final es de:$ "<<GG_vf<<endl;`

### Salida.
 
 La instrucción return provoca que la ejecución abandone la función main.
 
`return 0;`

## Cuenta moneda

### Descripcion del programa 

Este programa c++ permite ingresar el numero de monedas, para luego contar la cantidad de monedas que fueron ingresadas, tanto de 0.10 ctvs y 0.25 ctvs   y asi obtener la cantidad de monedas que fueron contadas.

### Funcionalidad 

1. Proceso de Inicio.

`#include<iostream>`

`using namespace std;`

`int main ()`

2. Declaramos las variables en la que vamos a almacenar los datos.

`int GG_n, GG_c=0, GG_c1=0, GG_c2=0;`

`float GG_x, GG_a=0, GG_a1=0, GG_a2=0;`

3. Pedimos al usuario que lea y ingrese la cantidad de monedas.

`cout<<"Cantidad de monedas a ingresar : ";`

`cin>>GG_n;`

4. Realizamos el proceso.

Utilizaremos la sentencia do-while se utiliza para especificar un ciclo condicional que se ejecuta. Ademas  en este caso usaremos los condicionales if-else,son una estructura de control, que nos permiten tomar cierta decisión al interior de nuestro algoritmo, es decir, nos permiten determinar que acciones tomar dada o no cierta condición.

`do{`

`cout<<"Ingrese el valor de la moneda (0.10,0.25) :";`

`cin>>GG_x;`

`GG_c=GG_c+1;`

`GG_a=GG_a+GG_x;`

`if(GG_x==0.10){`

`GG_c1=GG_c1+1;`

`GG_a1=GG_a1+GG_x;`

`}else{`

`GG_c2=GG_c2+1;`

`GG_a2=GG_a2+GG_x;`

`}`

`}while(GG_c<GG_n);`

5. Mostrar por pantalla.

`cout<<"El resultado fue:"<<endl;`

`cout<<"Cantidad de monedas ingresadas : "<<GG_c<<endl;`

`cout<<"Cantidad total en dinero contado : "<<GG_a<<endl;`

`cout<<"Cantidad de monedas de 0.10c ingresadas : "<<GG_c1<<endl;`

`cout<<"Cantidad total en dinero de monedas de 0.10cc : "<<GG_a1<<endl;`

`cout<<"Cantidad de monedas de 0.25cc ingresadas : "<<GG_c2<<endl;`

`cout<<"Cantidad total en dinero de mpnedas de 0.25cc : "<<GG_a2<<endl;`

### Salida.
 
 La instrucción return provoca que la ejecución abandone la función main.
 
`return 0;`

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
