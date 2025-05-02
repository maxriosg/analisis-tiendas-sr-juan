# 📊 Análisis de Desempeño de Tiendas - Desafío Data Science Latam

Este proyecto forma parte del **Challenge 1 - Data Science LATAM** de Alura y tiene como objetivo **analizar el desempeño de ventas de cuatro tiendas** y ayudar al Sr. Juan a tomar una decisión informada sobre **cuál de ellas vender**.

---

## 🎯 Objetivo

A partir de un conjunto de datos de ventas de cuatro tiendas, se realizaron análisis exploratorios y visualizaciones para:

- Calcular ingresos totales por tienda
- Identificar productos y categorías más/menos vendidos
- Calcular calificaciones promedio de los clientes
- Analizar los costos de envío promedio
- Explorar la distribución geográfica de las ventas
- Identificar la tienda menos productiva

---

## 🛠️ Herramientas utilizadas

- **Python 3**
- **Google Colab**
- **Pandas** – Manipulación de datos
- **Matplotlib / Seaborn** – Visualización de datos
- **Folium** – Mapas interactivos (opcional)
- **Jupyter Notebook / Google Colab** – Entorno de desarrollo

---

## 📂 Estructura del proyecto

```
├── challenge_tiendas.ipynb      # Notebook con análisis completo
├── README.md                    # Este archivo
```

---

## 📈 Análisis realizados

### ✔️ Ingresos totales por tienda
Se calcularon y visualizaron los ingresos, determinando que **Tienda 4** generó el menor ingreso.

### ✔️ Productos y categorías vendidas
Se identificaron:
- Las **categorías más populares**
- Los **productos más y menos vendidos**

### ✔️ Satisfacción del cliente
Se evaluaron las **calificaciones promedio**, donde **Tienda 4 tiene buena calificación**, pero bajo volumen de ventas.

### ✔️ Costos de envío
Tienda 4 presenta **uno de los costos de envío más altos**.

### ✔️ Análisis geográfico
Se exploraron las coordenadas (`lat`, `lon`) y se generaron:
- **Gráficos de dispersión geográfica**
- **Mapas de calor interactivos con Folium**
Se detectó que **Tienda 4 tiene menor densidad de ventas**, lo que refuerza su bajo rendimiento.

---

## 📌 Conclusión

Tras un análisis completo, se concluye que:

> **🔻 Tienda 4 es la menos productiva** y se recomienda su venta.  
> Esto se debe a sus bajos ingresos, bajo volumen de ventas, alto costo de envío y limitada presencia geográfica.

---

## 📝 Informe Final

Se redactó un informe profesional que incluye:

- Introducción al análisis
- Desarrollo con gráficos y visualizaciones
- Conclusión y recomendación clara

Puedes descargarlo desde el notebook.

---

## 🚀 Cómo ejecutar

1. Abre el archivo `challenge_tiendas.ipynb` en Google Colab.
2. Ejecuta cada celda para reproducir los análisis y gráficos.
3. (Opcional) Instala `folium` para visualizar los mapas interactivos:
   ```bash
   !pip install folium
   ```

---

## 📬 Contacto

Proyecto desarrollado como parte del curso de Data Science en español por [Alura Latam](https://www.aluracursos.com/).  
Para consultas: [maxrios@gmail.com]  
Repositorio creado por **[Maximiliano Ríos]**
