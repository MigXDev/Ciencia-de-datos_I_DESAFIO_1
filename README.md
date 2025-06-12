
  #                   INFORME FINAL DE TIENDAS - ANÁLISIS DE DATOS

<br>

Este proyecto presenta un análisis exploratorio de datos (EDA) aplicado a 
cuatro tiendas, utilizando Python y bibliotecas estándar como Pandas, Matplotlib 
y NumPy. El objetivo es obtener métricas clave sobre facturación, productos 
vendidos, satisfacción de clientes y costos de envío.

## CONTENIDO

1. Descripción del proyecto
2. Requisitos del sistema
3. Instrucciones de instalación
4. Ejecución del análisis
5. Estructura del análisis
6. Posibles problemas y soluciones
7. Créditos

-------------------------------------------------------------------------------
### 1. DESCRIPCIÓN DEL PROYECTO
-------------------------------------------------------------------------------

Se importan datos desde archivos CSV alojados en GitHub, correspondientes a 
cuatro ```(tienda_1.csv a tienda_4.csv).```  A partir de estos datos, se 
realiza un análisis comparativo para identificar tendencias y comportamientos 
comerciales clave.

Las variables analizadas incluyen:

- Precio de productos
- Categoría de productos
- Calificaciones de clientes
- Costos de envío
- Frecuencia de venta por producto

-------------------------------------------------------------------------------
### 2. REQUISITOS DEL SISTEMA
-------------------------------------------------------------------------------

Para ejecutar este proyecto es necesario contar con:

- Python 3.8 o superior
- Entorno recomendado: Jupyter Notebook, VS Code o cualquier IDE compatible

Bibliotecas necesarias:

- pandas
- matplotlib
- numpy

Instalación de dependencias:

```bash
pip install pandas matplotlib numpy
```

---
### 3. INSTRUCCIONES DE INSTALACIÓN
---

1. Clona este repositorio o descarga los archivos del proyecto.

2. Abre el archivo principal (por ejemplo, ```AluraStoreLatam.ipynb```)
en tu entorno de desarrollo.

3. Asegúrate de que las bibliotecas estén correctamente instaladas.

4. Ejecuta las celdas en orden para visualizar cada parte del análisis.

---
### 4. EJECUCIÓN DEL ANÁLISIS
---
Cada sección del código se encuentra comentada para facilitar su comprensión.
El análisis incluye:

- Ingresos totales por tienda (gráfico de barras)

- Cantidad de productos vendidos por categoría (gráfico tipo donut)

- Calificación promedio por tienda (barras horizontales)

- Producto más y menos vendido por tienda (comparativo con etiquetas)

- Costo de envío promedio por tienda (barras simples)

---
### 5. ESTRUCTURA DEL ANÁLISIS
---
El proyecto se estructura en cinco bloques principales:

- Importación de datos
- Cálculo de ingresos
- Análisis por categoría
- Evaluación de satisfacción del cliente
- Estudio de costos y volumen de productos

Los gráficos generados ayudan a interpretar visualmente los resultados.

---
### 6. POSIBLES PROBLEMAS Y SOLUCIONES
---
Si los gráficos no se muestran, asegúrate de ejecutar el entorno en modo
interactivo (por ejemplo, con %matplotlib inline en Jupyter).

Si falla la carga de datos, verifica la conexión a Internet y que las URLs
de los archivos ```.csv``` estén activas.

Si falta alguna biblioteca, vuelve a ejecutar ```pip install``` como se
indica en la sección 2.

---
### 7. CRÉDITOS
---
Este análisis fue desarrollado en el marco del Challenge Data Science LATAM
organizado por Alura, utilizando datos públicos y simulados.

Realizado por:
[<img src="https://avatars.githubusercontent.com/u/196855177?s=96&v=4" width=125><br><sub>Miguel Angel Ajhuacho</sub>](https://github.com/MigXDev) 
