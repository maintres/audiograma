


          
# Documentación del Sistema de Audiometría

## Descripción General
El sistema de audiometría es una aplicación web diseñada para realizar y registrar pruebas audiométricas. Permite la entrada de datos del paciente, la creación de audiogramas interactivos y la exportación de resultados en diferentes formatos.

## Estructura del Proyecto

### 1. Archivos Principales
- `index.php`: Archivo principal que contiene la interfaz de usuario y la lógica del sistema

### 2. Componentes Principales

#### 2.1 Datos del Paciente
- Formulario para ingresar información básica:
  - Nombre del paciente
  - DNI
  - Obra Social
  - Edad
  - Fecha del examen

#### 2.2 Audiograma
- Gráfico interactivo para representar los resultados de la audiometría
- Características:
  - Escala de frecuencias (Hz): 250, 500, 1000, 2000, 4000, 8000
  - Escala de intensidad (dB HL): -20 a 120
  - Cuadrícula con líneas de referencia
  - Marcadores diferenciados para cada tipo de medición

#### 2.3 Sistema de Marcadores
Símbolos utilizados en el audiograma:
- Oído Derecho:
  - Vía Aérea: Círculo rojo (O)
  - Vía Ósea: Triángulo rojo (◄)
- Oído Izquierdo:
  - Vía Aérea: X azul (X)
  - Vía Ósea: Triángulo azul (►)

### 3. Funcionalidades

#### 3.1 Entrada de Datos
- Interfaz intuitiva para ingresar valores audiométricos
- Validación de datos (-20 dB a 120 dB)
- Actualización en tiempo real del audiograma

#### 3.2 Visualización
- Gráfico responsive con Chart.js
- Cuadrícula clara y legible
- Diferenciación por colores (rojo: oído derecho, azul: oído izquierdo)
- Referencias visuales integradas

#### 3.3 Exportación
El sistema permite exportar los resultados en dos formatos:
- PDF: Incluye datos del paciente y audiograma
- Imagen (PNG): Captura del audiograma con datos del paciente

### 4. Tecnologías Utilizadas
- Frontend:
  - HTML5
  - CSS3 (Bootstrap 5.3.2)
  - JavaScript
- Bibliotecas:
  - Chart.js (v3.9.1): Para la generación del audiograma
  - jsPDF (v2.5.1): Para la exportación a PDF
  - html2canvas (v1.4.1): Para la captura de imagen
  - Bootstrap Icons (v1.11.1): Para iconografía

### 5. Diseño Responsivo
- Adaptación a diferentes tamaños de pantalla
- Scroll horizontal para el audiograma en dispositivos pequeños
- Diseño optimizado para visualización y uso en tablets y computadoras

### 6. Consideraciones de Uso
- Navegadores soportados: Modernos (Chrome, Firefox, Safari, Edge)
- Requisitos mínimos: Soporte para JavaScript y HTML5
- Conexión a Internet: Necesaria para cargar las bibliotecas CDN

### 7. Mantenimiento
Para mantener el sistema:
- Actualizar las bibliotecas CDN cuando sea necesario
- Verificar la compatibilidad con nuevas versiones de navegadores
- Realizar copias de seguridad periódicas del código

### 8. Recomendaciones
- Realizar pruebas antes de cada sesión de audiometría
- Verificar la calibración del sistema de audio
- Mantener actualizado el navegador web
- Guardar regularmente los resultados de las pruebas
![Informe_Audiometria](https://github.com/user-attachments/assets/da4f7fd0-398d-462f-acd6-7e95c389e86a)
