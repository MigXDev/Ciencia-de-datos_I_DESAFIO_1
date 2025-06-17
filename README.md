# ▌ INFORME FINAL DE TIENDAS - Challenge ALura Store  
═══════════════════════════════════════════════════════════

### ✦ ANÁLISIS EXPLORATORIO DE DATOS (EDA) ✦  

Este proyecto presenta un análisis exploratorio de datos (EDA) aplicado a cuatro tiendas, utilizando Python y bibliotecas estándar como `Pandas`, `Matplotlib` y `NumPy`. El objetivo es obtener métricas clave sobre facturación, productos vendidos, satisfacción de clientes y costos de envío.

---

## ▌ÍNDICE DE CONTENIDOS  
────────────────────────────

1. [Descripción del proyecto](#1--descripción-del-proyecto)  
2. [Requisitos del sistema](#2-requisitos-del-sistema)  
3. [Instrucciones de instalación](#3-instrucciones-de-instalación)  
4. [Ejecución del análisis](#4-ejecución-del-análisis)  
5. [Estructura del análisis](#5-estructura-del-análisis)  
6. [Posibles problemas y soluciones](#6-posibles-problemas-y-soluciones)  
7. [Créditos](#7-créditos)

## 1.  ▌DESCRIPCIÓN DEL PROYECTO  
────────────────────────────────────

Se importan datos desde archivos CSV alojados en GitHub, correspondientes a cuatro:

```text
tienda_1.csv  
tienda_2.csv  
tienda_3.csv  
tienda_4.csv  
```

A partir de estos datos, se realiza un análisis comparativo para identificar tendencias y comportamientos comerciales clave.

**Variables analizadas:**

- Precio de productos  
- Categoría de productos  
- Calificaciones de clientes  
- Costos de envío  
- Frecuencia de venta por producto

---

## 2. ▌REQUISITOS DEL SISTEMA  
────────────────────────────────────

**Lenguaje y entorno sugerido:**

- Python 3.8 o superior  
- Entorno recomendado: Jupyter Notebook, VS Code o cualquier IDE compatible  

**Dependencias necesarias:**

```bash
pip install pandas matplotlib numpy
```

Bibliotecas necesarias:

| **Pandas**      | **Matplotlib**      | **NumPy**     |
|:-----------------:|:-----------------:|:-----------------:|
|<img src="https://github.com/user-attachments/assets/9a938aa7-6c50-4142-aab8-68180fb072f9" width="120" alt="Pandas logo"> | <img src="https://github.com/user-attachments/assets/06721bd1-e433-4c99-aa2c-5799c9d2b286" width="120" alt="Matplotlib logo"> | <img src="https://numpy.org/images/logo.svg" width="120" alt="NumPy logo"> |

---

## 3. ▌INSTRUCCIONES DE INSTALACIÓN  
────────────────────────────────────────────

1. Cloná este repositorio o descargá los archivos del proyecto.  
2. Abrí el archivo principal (por ejemplo, `AluraStoreLatam.ipynb`) en tu entorno de desarrollo.  
3. Verificá que las bibliotecas necesarias estén instaladas.  
4. Ejecutá las celdas en orden para visualizar cada parte del análisis.

---

## 4. ▌EJECUCIÓN DEL ANÁLISIS  
───────────────────────────────────────

Cada sección del código está comentada para facilitar su comprensión.  
El análisis incluye los siguientes puntos destacados:

▸ Ingresos totales por tienda *(gráfico de barras)*  
▸ Cantidad de productos vendidos por categoría *(gráfico tipo donut)*  
▸ Calificación promedio por tienda *(barras horizontales)*  
▸ Producto más y menos vendido por tienda *(comparativo con etiquetas)*  
▸ Costo de envío promedio por tienda *(barras simples)*

---

## 5. ▌ESTRUCTURA DEL ANÁLISIS  
────────────────────────────────────────

El proyecto se organiza en cinco bloques principales:

1. Importación de datos  
2. Cálculo de ingresos  
3. Análisis por categoría  
4. Evaluación de satisfacción del cliente  
5. Estudio de costos y volumen de productos

> Todos los gráficos generados ayudan a interpretar visualmente los resultados.

---

## 6. ▌POSIBLES PROBLEMAS Y SOLUCIONES  
─────────────────────────────────────────────────────

◉ **Los gráficos no se muestran**  
→ Ejecutá el entorno en modo interactivo (por ejemplo, con `%matplotlib inline` en Jupyter).  

◉ **Error al cargar los datos**  
→ Verificá la conexión a Internet y que las URLs de los archivos `.csv` estén activas.  

◉ **Falta alguna biblioteca**  
→ Ejecutá nuevamente el comando:

```bash
pip install pandas matplotlib numpy
```
---

## 7. ▌CRÉDITOS  
────────────────────

Este análisis fue desarrollado como parte del **Challenge Data Science LATAM**, organizado por **Alura**, empleando datos públicos simulados con fines educativos.

**Autor:**  

| <img src="https://avatars.githubusercontent.com/u/196855177?s=96&v=4" width="125">|
|:-----------------:|
| *[Miguel Angel Ajhuacho](https://github.com/MigXDev)* |




**Contacto profesional:**  
- GitHub: [@MigXDev](https://github.com/MigXDev)  
- LinkedIn: *[Miguee](https://www.linkedin.com/in/ctrl-z--migue-ajh/)*  
