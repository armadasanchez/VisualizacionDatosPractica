
# **Evolución de Tendencias en el Mundo del Cine**

https://github.com/armadasanchez/VisualizacionDatosPractica

Este proyecto es un dashboard interactivo desarrollado con Python y Dash para analizar y visualizar métricas clave en el mundo del cine. Permite explorar datos como calificaciones de la audiencia, valoraciones de críticos y número de votos en función de características como géneros, clasificaciones, y duración de las películas.

## **Características del Dashboard**
1. **Gráfico de violín**:
   - Muestra la distribución de las calificaciones por clasificación de películas (e.g., PG, PG-13, R).
   - Permite analizar cómo varían las puntuaciones dentro de cada clasificación.
   
2. **Gráfico de barras apiladas**:
   - Visualiza el promedio de la métrica seleccionada para cada género de película.
   - Ayuda a identificar qué géneros tienen mejor desempeño.

3. **Gráfico de dispersión**:
   - Relaciona la duración de las películas con la métrica seleccionada.
   - Ideal para explorar si existe una correlación entre el tiempo de duración y el éxito de las películas.

4. **Gráfico de torta**:
   - Muestra la proporción de películas en función del género o la clasificación.
   - Permite cambiar entre género y clasificación usando un desplegable.

## **Requisitos Previos**
Asegúrate de tener instalados los siguientes paquetes en tu entorno de Python:
- **Dash**: Framework para crear aplicaciones web interactivas.
- **Plotly**: Biblioteca para gráficos interactivos.
- **Pandas**: Manejo y análisis de datos.

### Instalación
Para instalar las dependencias necesarias, ejecuta:
```bash
pip install dash pandas plotly
```

## **Ejecución del Proyecto**
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/usuario/proyecto-cine.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd proyecto-cine
   ```
3. Ejecuta el archivo principal:
   ```bash
   python app.py
   ```
4. Abre el navegador en `http://127.0.0.1:8050/` para interactuar con el dashboard.

## **Estructura del Proyecto**
```
proyecto-cine/
│
├── app.py                # Archivo principal de la aplicación Dash
├── README.md             # Documentación del proyecto
├── data/
│   └── movies.csv        # (Opcional) Dataset de películas utilizado
├── assets/               # (Opcional) Archivos de estilo adicionales
```

## **Descripción del Dataset**
El dataset contiene información relevante sobre películas, incluyendo:
- **Título**: Nombre de la película.
- **Año**: Año de lanzamiento.
- **Géneros**: Lista de géneros asociados a cada película.
- **Clasificación**: Calificación por edades (e.g., PG, R).
- **Duración**: Duración de la película en minutos.
- **Calificaciones**: Incluye las notas de la audiencia y de los críticos.
- **Número de votos**: Cantidad total de votos de la audiencia.

## **Cómo Usar el Dashboard**
1. Selecciona la métrica que deseas analizar usando el desplegable (e.g., calificación de la audiencia, número de votos).
2. Ajusta el rango de años para filtrar las películas del periodo de interés.
3. Explora los gráficos interactivos:
   - Analiza distribuciones, tendencias y correlaciones.
   - Cambia entre género y clasificación en el gráfico de torta para observar proporciones.

## **Personalización**
El dashboard está diseñado para ser extensible:
- Puedes integrar nuevos gráficos o métricas.
- Ajusta el diseño añadiendo estilos CSS personalizados en el directorio `assets/`.

## **Contribuciones**
Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:
1. Haz un fork del repositorio.
2. Crea una rama para tu funcionalidad:
   ```bash
   git checkout -b nueva-funcionalidad
   ```
3. Realiza tus cambios y súbelos a tu rama.
4. Crea un Pull Request describiendo las mejoras.

## **Licencia**
Este proyecto está bajo la Licencia GPL-2.0 license. Siéntete libre de usarlo y modificarlo según tus necesidades.
