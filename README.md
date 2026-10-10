# 🎲 Ruleta · Asistente Estadístico

![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)
![Estado](https://img.shields.io/badge/estado-activo-success.svg)
![Tecnologías](https://img.shields.io/badge/tecnologías-HTML5%20%7C%20CSS3%20%7C%20JS--ES6-orange.svg)

Un asistente avanzado e interactivo de análisis estadístico para ruleta diseñado para ser utilizado tanto en dispositivos **móviles** como de **escritorio**. 

⚠️ **Aviso Matemático:** *Cada tirada en la ruleta es un evento independiente. La esperanza matemática de cualquier sistema de apuestas en la ruleta es estrictamente negativa. Este asistente tiene un propósito únicamente educativo y estadístico para la gestión de banca y análisis de patrones.*

---

## 🚀 Características Principales

- 📊 **Modelo de Gravedad de Rueda:** Algoritmo que calcula la influencia y atracción de posiciones físicas en el cilindro según la frecuencia histórica y el peso reciente.
- 📱 **Diseño Híbrido Responsivo:** Interfaces diferenciadas y optimizadas para teléfono móvil y pantalla de escritorio.
- 💾 **Persistencia Automática (`localStorage`):** Guarda automáticamente tu historial, saldo de banca, rachas y configuraciones para que no pierdas nada al refrescar la página.
- 📥 **Exportación a CSV:** Descarga el historial completo de las tiradas para realizar análisis detallados en Excel, Google Sheets o Python.
- 🎨 **Tema Claro / Oscuro:** Cambia de modo oscuro a modo claro según tu entorno de luz.
- 🎤 **Entrada de Datos Avanzada:** Incluye entrada táctil rápida y soporte de comandos de voz en móviles (ej. *"Sale 17 negro"*).
- 📈 **Gestión de Banca y Progresiones:** Soporte para sistemas Plano, Martingala, Fibonacci y D'Alembert.

---

## ⚙️ Estrategias y Criterios Disponibles

### Tipos de Apuesta
1. **Números Plenos (1 a 18 números)**
2. **Color** (Rojo / Negro)
3. **Paridad** (Par / Impar)
4. **Mitades** (Falta 1-18 / Pasa 19-36)
5. **Docenas** (1ª, 2ª, 3ª)
6. **Columnas** (Columna 1, 2, 3)

### Criterios de Selección
- **Gravedad de Rueda:** Supresión gaussiana sobre zonas calientes físicas del cilindro.
- **Caliente:** Selecciona los sectores o números con mayor frecuencia.
- **Frío / Atrasado:** Selecciona las posiciones con menor frecuencia o que llevan más tiempo sin salir.
- **Z-Score:** Análisis de desviación estándar respecto a la distribución uniforme esperada.
- **Vecinos:** Cobertura de sectores contiguos al último número acontecido.

---

## 🛠️ Instalación y Uso

No requiere compilación ni servidores de backend. La aplicación funciona 100% en el navegador (Client-Side).

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/daesdel/ruleta_asistente.git
   cd ruleta_asistente
   ```
2. **Ejecutar la aplicación:**
   Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Safari, Firefox, Edge).

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de modificarlo, adaptarlo y mejorarlo.
