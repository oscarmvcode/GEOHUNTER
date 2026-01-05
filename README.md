# 🌍 GEOHUNTER: Extreme Time Trial

**GEOHUNTER** es un simulador de reconocimiento geográfico de alto rendimiento. El desafío consiste en localizar coordenadas exactas en un mapa mundial bajo presión de tiempo extrema. Este proyecto ha sido diseñado con un enfoque **Mobile-First**, garantizando una respuesta táctil ágil y una interfaz limpia.

---

## 🚀 Características Principales

* **Motor Geodésico:** Cálculo de distancias en tiempo real utilizando la fórmula de Haversine para una precisión milimétrica.
* **Interfaz Modernista:** UI basada en *Glassmorphism* (efecto cristal) construida con **Tailwind CSS**.
* **Base de Datos Global:** Más de 600 locaciones estratégicas precargadas (capitales, metrópolis y puntos clave).
* **Optimización Móvil:** Control táctil adaptativo, bloqueo de zoom accidental y botones de gran tamaño para jugabilidad con pulgares.
* **Dificultad Progresiva:** 4 niveles de intensidad:
    * 🟢 **FÁCIL:** 20 segundos.
    * 🟡 **MEDIO:** 10 segundos.
    * 🟠 **DIFÍCIL:** 5 segundos.
    * 🔴 **ULTRA:** 3 segundos.

---

## 🛠️ Stack Técnico

El proyecto utiliza una arquitectura ligera para asegurar la carga instantánea:

* **Frontend:** HTML5 / CSS3 Puro.
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (Framework de utilidad).
* **Mapas:** [Leaflet.js](https://leafletjs.com/) (Biblioteca de mapas interactivos de código abierto).
* **Lógica:** JavaScript Vanilla (ES6+).

---

## 📐 Lógica de Precisión

El sistema evalúa el éxito basándose en la distancia esférica entre el clic del usuario y el objetivo real. 



Se utiliza la constante del radio terrestre $R = 6371$ km. Si el usuario marca un punto a más de **500 km** de distancia, se descuenta una vida automáticamente.

---

## 📱 Guía de Optimización Mobile

| Característica | Implementación |
| :--- | :--- |
| **Viewport** | Ajustado para evitar el re-escalado del navegador. |
| **Interacción** | Eventos `click` optimizados para respuesta táctil rápida. |
| **UI Dinámica** | El HUD se adapta automáticamente a pantallas desde 320px. |
| **Rendimiento** | Renderizado de tiles de mapa optimizado para bajo consumo de datos. |

---

## 🕹️ Instalación

1. Descarga el archivo `index.html`.
2. Asegúrate de tener conexión a internet (para cargar los estilos y el mapa).
3. Abre el archivo en tu navegador favorito (Chrome, Safari o Firefox recomendado).

---

**GEOHUNTER** - *Desarrollado para mentes rápidas y amantes de la geografía.*
