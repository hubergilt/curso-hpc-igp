# curso-hcp-igp

## Clase 1

Ejemplos de introduccion a C, salida y entrada estandar (libreria stdio.h).

## Clase 2

Ejemplos de funciones, punteros y asignacion dinamica de memoria (libreria stdlib.h).

## Clase 3

Ejemplos de estructuras, hilos, barreras y herramienta gprof (libreria pthread.h).

## Clase 4

Ejemplos de sincronizacion con exclusion mutua, uniendo hilos, midiendo el tiempo de ejecucion, comparando programa serial vs paralelo y barreras (libreria pthread.h).

![Grafico de Hilos](clase04/time_vs_threads.png "Tiempo en segundo vs numero de hilos")

## Clase 5

Ejemplos de corrimiento de bits, principios de localidad espacial y temporal, orden por filas y asignacion continua de direcciones de memoria. (libreria time.h)


## Clase 6

Introduccion a fortran 95, ejemplos de salida y entrada estandar, numeros, bloques program, lazos do, condicionales if-else y funciones (paso por valor).

## Clase 7

Ejemplos de subrutinas (paso por referencia), bloques de modulos, alias de subrutinas, arreglos estaticos, arreglos dinamicos, arreglos de primer orden y segundo orden, numeros aleaorios con semilla, formato para numeros y cadenas de caracteres, estructuras de datos (type) y arreglo de estructuras (type).

## Clase 8

Ejemplos de MPI con fortran 95, iniciar MPI con MPI_INIT, identificar el id del proceso (rankid) con MPI_COMM_RANK, obtener el numero de procesos con MPI_COMM_SIZE, enviar mensajes con MPI_SEND, recibir mensajes con MPI_RECV por el comunicador MPI_COMM_WORLD y terminar el proceso con MPI_COMM_FINALIZE. Paso de mensajes tipo datos enteros y arreglos.

## Clase 9

Ejemplos de MPI con fortran 95, para enviar y recibir enteros y arreglos usando MPI_SEND y MPI_RECV.

## Clase 10

Ejemplos de MPI con fortran 95, enviando y recibiendo datos usando broadcast MPI_BCAST y barreras MPI_BARRIER, partiendo datos usando scatter MPI_SCATTER, componiendo datos usando MPI_GATHER y usando operaciones de reduccion MPI_REDUCE.

## Clase 11

Repaso de operaciones MPI_REDUCE, para suma MPI_SUM y producto MPI_PROD, generar archivos HDF5, con el comando h5fc, invocar c desde fortran y fortran desde c

## Laboratorio 1

* Programar una calculador con menu con c
* Programa multiplicación de matrices cuadras con c

## Laboratorio 2

* Programar paralelizar la operacion de multiplicación de matrices, utilizando hilos con librería pthread

* Gráfica de la multiplicación de matrices paralelo nodo master
![Grafico de Multiplicacion de Matrices paralelo](laboratorio2/medida_master.png "Gráfica de la multiplicación de matrices paralelo nodo master")

* Gráfica de la multiplicación de matrices paralelo nodo computo
![Grafico de Multiplicacion de Matrices paralelo](laboratorio2/medida_computo.png "Gráfica de la multiplicación de matrices paralelo nodo computo")

## Laboratorio 3

* Programar una calculador con menu con fortran 95
* Programa multiplicación de matrices cuadras con fortran 95

## Laboratorio 4

* Programa en Fortran para la multiplicacion de dos matrices, utilizando MPI

* Gráfica de la multiplicación de matrices en sequencial y en paralelo usando MPI, sobre el de nodo computo
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Programa_sequencial_y_paralelo_np%3D1.png "Gráfica de la multiplicación de matrices en sequencial y paralelo usando MPI")

* Gráfica de la multiplicación de matrices en paralelo usando MPI, desde 1 hasta 12 CPUs
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Programa_paralelo_de_np%3D1_hasta_np%3D12.png "Gráfica de la multiplicación de matrices paralelo usando MPI desde 1 hasta 12 CPUs")

* Gráfica de la multiplicación de matrices en paralelo usando MPI, desde 13 hasta 24 CPUs
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Programa_paralelo_de_np%3D13_hasta_np%3D24.png "Gráfica de la multiplicación de matrices paralelo usando MPI desde 13 hasta 24 CPUs")

* Gráfica de la multiplicación de matrices en paralelo usando MPI, desde 25 hasta 36 CPUs
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Programa_paralelo_de_np%3D25_hasta_np%3D36.png "Gráfica de la multiplicación de matrices paralelo usando MPI desde 25 hasta 36 CPUs")

* Gráfica de la multiplicación de matrices en paralelo usando MPI, desde 37 hasta 48 CPUs
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Programa_paralelo_de_np%3D37_hasta_np%3D48.png "Gráfica de la multiplicación de matrices paralelo usando MPI desde 37 hasta 48 CPUs")

* Gráfica de la multiplicación de matrices en paralelo usando MPI, duración vs el número de procesadores para dos matrices de 5000x5000 y un tamaño del problema de 600MB.
![Grafico de Multiplicacion de Matrices paralelo](laboratorio4/Duracion_vs_Numero_de_procesadores_NB%3D600MB.png "Gráfica duración vs número de procesadores para una tamaño del problema de 600MB")



## Laboratorio 5

* Programa en Fortran para la multiplicacion de dos matrices, utilizando operaciones MPI : Broadcast, Scatter y Gatter y guardar la salidas en formato HDF5

* Gráfica de la multiplicación de matrices en sequencial y en paralelo operaciones MPI, sobre el de nodo computo
![Grafico de Multiplicacion de Matrices paralelo](laboratorio5/mpi_oper01.png "Gráfica de la multiplicación de matrices en sequencial y paralelo usando operaciones MPI")

* Gráfica de la multiplicación de matrices en paralelo usando operaciones MPI, para 2, 4, 8, 16 y 32 CPUs
![Grafico de Multiplicacion de Matrices paralelo](laboratorio5/mpi_oper02.png "Gráfica de la multiplicación de matrices paralelo utilizando operaciones MPI, para 2, 4, 8, 16 y 32 CPUs")

* Gráfica de la multiplicación de matrices en paralelo usando operaciones MPI, comparacion con el programa sequencial
![Grafico de Multiplicacion de Matrices paralelo](laboratorio5/mpi_oper03.png "Gráfica de la multiplicación de matrices paralelo usando operaciones MPI, comparacion con el programa sequencial")

* Gráfica de la multiplicación de matrices en paralelo usando operaciones MPI, comparacion con el programa MPI
![Grafico de Multiplicacion de Matrices paralelo](laboratorio5/mpi_oper04.png "Gráfica de la multiplicación de matrices paralelo usando operaciones MPI, comparacion con el programa MPI")

## Laboratorio 6

* Programa calculadora en FORTRAN, con las funciones desde C y programar multiplicacion de matrices con FORTRAN
