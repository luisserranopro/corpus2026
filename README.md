# Feria del Corpus - Granada 2026 💃🍷

¡Bienvenido a mi aplicación móvil y PWA del **Corpus de Granada 2026**! 

Esta aplicación ha sido diseñada y desarrollada en **Flutter (Dart)** como un prototipo interactivo para ayudar a granadinos y visitantes a exprimir al máximo la Fiesta Mayor de la ciudad. Cuenta con un diseño flamenco tradicional (patrón de lunares andaluces en la interfaz) y mecánicas modernas de gamificación para incentivar la visita a las casetas.

---

## 📱 Características Principales

### 1. 🏠 Inicio Dinámico (Home)
* **Cuenta atrás interactiva en tiempo real** para los grandes hitos de la feria (El Pregón de las Fiestas, la noche del Alumbrado, la salida de La Tarasca y la solemne Procesión del Corpus Christi).
* **Sugerencias inteligentes**: Muestra 3 actividades aleatorias de la programación oficial que aún no han ocurrido, con un botón interactivo de refresco.
* **Detalle rápido de transporte**: Información integrada sobre cómo llegar al ferial de Almanjáyar en autobús urbano (Líneas F1 a F6) y alertas críticas de servicio en tiempo real (aviso de huelga de metro).

### 2. 🎪 Directorio de Casetas Oficiales
* Base de datos completa con las **68 casetas oficiales** adjudicadas para la feria en 2026, incluyendo titularidad, tipo de caseta (Tradicional o Institucional) y su número de módulo/calle exacto.
* Buscador en tiempo real y filtros rápidos por tipología.
* **Pasaporte de Sello Digital**: Un sistema que permite al usuario sellar la caseta que está visitando con su huella, registrando la fecha y hora de su visita en el almacenamiento local.

### 3. 📅 Programa & Búsqueda Cruzada
* Agenda completa del Corpus organizada cronológicamente.
* Buscador integrado para encontrar eventos de casetas específicas.
* **Búsqueda Cruzada**: Al pulsar sobre cualquier evento del programa, se abre un panel inferior que busca la caseta en la base de datos y te dice exactamente en qué calle y módulo del ferial se celebra.

### 4. 📊 Mi Corpus (Wrapped)
* Pantalla de estadísticas personalizadas al estilo de los famosos "Wrapped" de fin de año.
* Analiza tus sellos guardados localmente para mostrarte:
  * El recuento total de casetas visitadas.
  * Tu caseta favorita (la que más has sellado).
  * Dónde empezó tu feria (primera visita con fecha y hora).
  * Tu última parada (última caseta visitada).

### 5. 📥 Instalación PWA (Instalar)
* Una pestaña dedicada a guiar al usuario paso a paso para añadir la app a la pantalla de inicio de su dispositivo, tanto en **iOS (Safari)** como en **Android (Chrome)**.

---

## 🛠️ Tecnologías Utilizadas

* **Flutter / Dart**: Para el desarrollo de la interfaz fluida multiplataforma.
* **SharedPreferences**: Para persistir localmente y de forma segura el pasaporte de sellos y visitas del usuario sin necesidad de base de datos externa.
* **CustomPaint / PolkaDotPainter**: Dibujo matemático y nativo del patrón de lunares andaluces en alta resolución sin sobrecargar la app con imágenes de fondo pesadas.

---

## 🚀 Instalación y Configuración Local

Sigue estos pasos para ejecutar el proyecto en tu máquina local:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/luisserranopro/corpus2026.git](https://github.com/luisserranopro/corpus2026.git)
cd corpus2026
