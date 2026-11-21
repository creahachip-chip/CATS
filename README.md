CATS - Creahachip Automated Trading System
Bienvenido al repositorio oficial de CATS, el núcleo del sistema de negociación electrónica y simulación de mercado de Creahachip.


# Descripción General 

CATS es una plataforma avanzada diseñada para simular un entorno de mercado financiero real (tipo NASDAQ o Forex) dentro del ecosistema de Creahachip. Su arquitectura está optimizada para la ejecución de algoritmos de Inteligencia Artificial (IA) y estrategias de trading automatizado sin intervención humana, conectando con fuentes de datos reales en tiempo real.

Este proyecto sirve como banco de pruebas para desarrolladores de algoritmos y operadores, permitiendo operar con cuentas demo (fondos ficticios) utilizando datos de mercado en vivo, garantizando un entorno seguro y libre de riesgo para testear estrategias antes de su implementación en sistemas reales.

# Características Principales

Simulación en Tiempo Real: Conexión vía WebSockets a APIs públicas de mercado (Cripto, Forex, Índices) para mostrar gráficos de velas y cotizaciones exactas en vivo.

Ejecución Autónoma por IA: Diseñado para integrarse con agentes de IA (como Tay-AI) que envían órdenes de compra/venta automáticamente mediante scripts externos.

Gestión de Cuentas Demo: Sistema de contabilidad virtual que maneja saldos, historial de transacciones y cálculo de PnL (Ganancias y Pérdidas) sin dinero real.

Interfaz Web Moderna: Gráficos de velas interactivos y paneles de control limpios para visualizar el mercado y el rendimiento del algoritmo.

Arquitectura Serverless: Desplegado en la nube para máxima disponibilidad y escalabilidad.

## Tecnologías y Lenguajes Utilizados

| Componente | Tecnología / Lenguaje | Función |
| :--- | :--- | :--- |
| **Frontend (Interfaz)** | HTML5, CSS3, JavaScript (ES6+) | Interfaz del simulador, controles de orden y panel de cuenta |
| **Gráficos** | TradingView Lightweight Charts | Renderizado de velas japonesas e indicadores en el navegador |
| **Datos en Vivo** | WebSockets / REST APIs | Recepción de cotizaciones y velas desde fuentes públicas |
| **Backend / API** | Cloudflare Workers (JavaScript) | Validación de órdenes demo, cálculo de PnL y lógica de negocio |
| **Base de Datos** | Cloudflare D1 (SQLite) | Almacenamiento de cuentas demo, historial y registros de operaciones |
| **Hosting Estático** | GitHub Pages | Publicación y entrega de los archivos frontend |

## Estructura del Repositorio

```text
CATS/
├── index.html
├── style.css
├── app.js
├── README.md
└── assets/
```

## Primeros Pasos

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/TU_USUARIO/CreahachipAutomatedTradingSystem.git
   ```
2. **Ejecutar el frontend:**
   Abre `index.html` en tu navegador o publícalo mediante **GitHub Pages**.
3. **Conectar el backend:**
   Despliega tu **Cloudflare Worker** vinculado a tu base de datos **D1** y apunta la URL de tu API desde `app.js`.

## Licencia

Este proyecto se distribuye bajo licencia MIT. Consulta el archivo `LICENSE` para más detalles.

2026   prohibido copiar sin permiso del administrador 
