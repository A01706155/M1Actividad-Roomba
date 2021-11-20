## <center> Tecnológico de Monterrey
### <center> Modelación de sistemas multiagentes con gráficas computacionales. (TC2008B.1) <br>M1. Actividad<br><br>Manolo Ramírez Pintor<br>A01706155<br>ITESM Campus Querétaro<br>19/11/2021<br>

# Actividad del Módulo 1
### **Link del GitHub:** https://github.com/A01706155/M1Actividad-Roomba

## Limpieza mediante robots tipo agentes
En esta tarea se nos pide realizar un informe y un programa que observe las estadísitcas de un robot de limpieza reactivo.

## Reglas
**Tenemos que poder dar los siguientes datos:**
 1. Tamaño del grid
 2. Número de agentes (robots) que intentarán limpiar
 3. Porcentaje de celdas inicialmente sucias
 4. Tiempo máximo de ejecución

**Procedimiento que debemos meter:**
1. Inicializar las celdas sucias 
2. Inicializar los agentes en [1,1

**Ejecución del programa**
1. Si el agente se encuentra en una celda sucia, se limpia
2.  Si el agente está en una celda limpia, este se desplaza a una dirección aleatoria dentro del rango de celdas que se puede desplazar a su alrededor (8), si no se puede mover, se va a quedar donde mismo.
3. Debe existir un tiempo de ejecución máximo para que el programa no corra para siempre en caso de que algo raro pase. 

**Depués de que se ejecute...**
Se debe poder ver:
1. El tiempo en el que las celdas se limpiaron
2. Porcentaje de celdas que pudieron limpiarse
3. El numero de movimientos realizado por los agentes

**Adicionalmente...**
En el documento se debe mostrar *"¿Cómo la cantidad de agentes impacta al tiempo que toma en limpiar las celdas?"*