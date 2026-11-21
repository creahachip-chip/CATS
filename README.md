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

# Tecnologías y Lenguajes Utilizados

CATS utiliza un stack tecnológico moderno enfocado en el rendimiento y la eficiencia en la nube:


Componente	           Tecnología / Lenguaje                    	Función				
Frontend (Interfaz)	HTML5, CSS3, JavaScript (ES6+)	        Visualización de gráficos, paneles de control y experiencia de usuario.				
Librería de Gráficos    	Lightweight Charts (TradingView)	Renderizado de velas japonesas e indicadores técnicos de alto rendimiento.				
Datos de Mercado	      WebSockets / REST APIs	            Recepción de precios en tiempo real desde fuentes públicas.				
Backend / Lógica	Cloudflare Workers (JavaScript / ES модули)	Motor de simulación, gestión de cuentas, validación de órdenes y seguridad.				
Base de Datos	Cloudflare D1 (SQLite)	Almacenamiento de historiales de usuario, saldos y logs de operaciones.				
Infraestructura	GitHub Pages	Alojamiento de la interfaz web estática.				
						
