<div align="center">

# 📈 Crypto Simulador 📉

**Un simulador de inversión en criptomonedas simple y elegante, construido con JavaScript puro, TailwindCSS y la API de CoinGecko.**

</div>

<p align="center">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="TailwindCSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
  <img alt="CoinGecko API" src="https://img.shields.io/badge/API-CoinGecko-8BC34A?style=for-the-badge&logo=coingecko&logoColor=white">
</p>

---

## ✨ Características Principales

Este proyecto es una aplicación 100% *client-side* (no necesita base de datos ni backend) y incluye:

* **📊 Ranking en Tiempo Real:** Visualiza las principales criptomonedas del mercado con sus precios y variaciones de las últimas 24 horas.
* **🔍 Búsqueda y Filtrado:** Busca monedas específicas por su ID (ej: `bitcoin`) o filtra la lista por rendimiento (positivas, negativas) y precio (ascendente, descendente).
* **⭐ Sistema de Favoritos:** ¿Te gusta una moneda? ¡Márcala con la estrella! La aplicación la guardará en tu página de "Favoritos" para un acceso rápido.
* **💼 Simulación de Portfolio Realista:**
    * **Compra por Cantidad:** Simula la compra de una cantidad específica de monedas (ej: 2 `ethereum`).
    * **Compra por USD:** Simula una inversión con una cantidad fija de dinero (ej: gastar $100 en `cardano`).
    * **Cálculo de P/L:** El sistema calcula tu "Cost Basis" (coste medio de adquisición) y te muestra tu **Ganancia o Pérdida Total** real, no solo la fluctuación diaria.
* **💾 Persistencia de Datos:** Tu portfolio y tu lista de favoritos se guardan localmente en tu navegador usando `localStorage`, para que no pierdas tus datos al recargar la página.
* **👤 Simulación de Sesión:** Un saludo de bienvenida que guarda tu nombre.

---

## 🛠️ Tecnologías Utilizadas

* 🟡 **JavaScript (ES6+):** Utilizado para toda la lógica de la aplicación, peticiones `fetch` a la API, manipulación del DOM y gestión del `localStorage`.
* 🔵 **TailwindCSS:** Para un diseño moderno, *responsive* y rápido sin una sola línea de CSS tradicional.
* ⚪ **HTML5 Semántico:** Estructura limpia y accesible.
* 🦎 **API de CoinGecko:** Provee todos los datos de precios, logos y mercado en tiempo real.
* 💾 **LocalStorage:** Para la persistencia de datos del usuario en el navegador.


## 🧪 Prueba el Proyecto

* Puedes probar la aplicación aquí:

* 👉 [Pagina de criptomonedas](https://criptomonedaspruebaweb.vercel.app/)
