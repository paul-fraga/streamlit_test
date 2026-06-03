# 🪙 Simulador Interactivo de Probabilidad

Esta es una aplicación web interactiva desarrollada en Python. El proyecto emula el lanzamiento de una moneda al azar múltiples veces y calcula el valor medio de los resultados. A medida que aumenta el número de intentos, la aplicación traza el progreso en tiempo real, demostrando cómo el valor medio calculado se acerca a su valor real (0.5).

**🔴 <a href="https://streamlit-test-g140.onrender.com" target="_blank">Ver la Aplicación en Vivo</a>**

### 🛠️ Herramientas y Tecnologías
* **Lenguaje:** Python
* **Framework Web:** Streamlit
* **Manipulación de Datos:** Pandas
* **Análisis Estadístico:** SciPy
* **Despliegue Cloud:** Render

### 💡 Características Principales
* Interfaz gráfica intuitiva utilizando widgets como botones y controles deslizantes (sliders).
* Actualización dinámica de gráficos en tiempo real.
* Almacenamiento del historial de experimentos mediante el uso de variables de estado de sesión (`st.session_state`) para mantener los valores en ejecuciones continuas.

### 🚀 Cómo ejecutar este proyecto localmente

Si deseas probar la aplicación en tu propio entorno, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener instaladas las dependencias listadas en el archivo `requirements.txt`.
3. Ejecuta la aplicación desde la línea de comandos en la carpeta raíz del proyecto: streamlit run app.py
4. streamlit run app.py
```bash
   pip install pandas scipy streamlit
