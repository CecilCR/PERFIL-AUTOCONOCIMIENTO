# 📊 Sistema de Evaluación de Autoconocimiento

Sistema interactivo de evaluación psicométrica para el desarrollo de competencias de autoconocimiento en contextos organizacionales. Basado en los instrumentos de **Whetten & Cameron**.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🎯 Descripción

Herramienta web autocontenida que evalúa tres dimensiones fundamentales del autoconocimiento profesional:

- **Estilo Cognoscitivo**: Cómo procesas información (Planeación, Creatividad, Conocimiento)
- **Locus de Control**: Percepción sobre el control de tu destino (Interno, Equilibrado, Externo)
- **Tolerancia a la Ambigüedad**: Capacidad para manejar incertidumbre (Novedad, Complejidad, Insolubilidad)

## ✨ Características

- ✅ **Sin dependencias externas** - Funciona completamente offline
- ✅ **Responsive** - Compatible con desktop, tablet y móvil
- ✅ **Validación robusta** - Detecta respuestas incompletas y patrones inconsistentes
- ✅ **Feedback personalizado** - Retroalimentación específica según resultados
- ✅ **Interfaz intuitiva** - Barras de progreso y navegación clara
- ✅ **Cálculos verificados** - Algoritmos validados con casos de prueba exhaustivos
- ✅ **Listo para imprimir** - Resultados exportables en PDF

## 🚀 Uso

### Opción 1: Uso directo
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/autoconocimiento-evaluacion.git

# Abrir en navegador
open perfil-autoconocimiento-completo.html
```

### Opción 2: GitHub Pages
El sistema está disponible en: `https://tu-usuario.github.io/autoconocimiento-evaluacion/`

## 📋 Estructura de las Evaluaciones

### 1. Estilo Cognoscitivo (18 preguntas)
- **Escala:** 1 (Totalmente en desacuerdo) - 5 (Totalmente de acuerdo)
- **Dimensiones:**
  - Planeación (7 preguntas)
  - Creativo (7 preguntas)
  - Conocimiento (4 preguntas)
- **Interpretación:** Promedios independientes por dimensión

### 2. Locus de Control (29 preguntas)
- **Formato:** Opción A o B (24 preguntas válidas, 5 neutrales)
- **Orientaciones:**
  - Interna (0-10 puntos): Perfil Protagonista
  - Equilibrada (11-13 puntos): Perfil Realista
  - Externa (14-24 puntos): Perfil Análisis Sistémico
- **Cálculo:** Conteo de respuestas externas

### 3. Tolerancia a la Ambigüedad (16 preguntas)
- **Escala:** 1 (Totalmente en desacuerdo) - 7 (Totalmente de acuerdo)
- **Subescalas:**
  - Novedad (4 preguntas)
  - Complejidad (9 preguntas)
  - Insolubilidad (3 preguntas)
- **Procesamiento:** Inversión automática de reactivos pares
- **Interpretación:**
  - Alta Tolerancia (1.0-4.0)
  - Moderada (4.1-5.0)
  - Baja Tolerancia (5.1-7.0)

## 🔍 Validación Técnica

El sistema incluye:

- ✅ Validación de completitud de respuestas
- ✅ Detección de patrones inconsistentes (respuestas automáticas)
- ✅ Scroll automático a preguntas sin responder
- ✅ Persistencia visual de respuestas al cambiar tabs
- ✅ Cálculos matemáticos verificados con tests unitarios

Ver documentación completa en [`VALIDACION_TECNICA.md`](VALIDACION_TECNICA.md)

## 📊 Casos de Uso

### Académico
- Cursos de desarrollo organizacional
- Programas de liderazgo
- Talleres de autoconocimiento
- Investigación en psicología organizacional

### Empresarial
- Procesos de selección
- Programas de desarrollo de talento
- Coaching ejecutivo
- Team building

### Personal
- Autodiagnóstico de competencias
- Desarrollo profesional
- Preparación para entrevistas

## 🎓 Fundamento Teórico

Basado en:
- **Whetten, D. A., & Cameron, K. S.** (2016). *Developing Management Skills* (9th ed.)
- Escalas psicométricas validadas en contextos organizacionales
- Framework de competencias directivas

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Diseño responsive y animaciones
- **JavaScript (Vanilla)** - Lógica de negocio sin frameworks
- **LocalStorage** - Persistencia opcional de datos

## 📖 Documentación

- [`VALIDACION_TECNICA.md`](VALIDACION_TECNICA.md) - Especificaciones técnicas y casos de prueba
- Comentarios inline en el código fuente
- Fórmulas de cálculo documentadas

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Changelog

### v1.0.0 (2026-02-05)
- ✅ Implementación completa de las tres evaluaciones
- ✅ Validación exhaustiva de cálculos
- ✅ Detección de patrones inconsistentes
- ✅ Interfaz responsive
- ✅ Feedback personalizado por nivel
- ✅ Textos pedagógicamente optimizados

## ⚖️ Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍🏫 Autor

Desarrollado para el curso **"Gestión de las relaciones en las organizaciones"**

## 🙏 Agradecimientos

- Whetten & Cameron por los instrumentos originales
- Comunidad académica de psicología organizacional
- Estudiantes que participaron en las pruebas piloto

---

## 📞 Contacto

Para preguntas, sugerencias o reportar bugs:
- 📧 Email: tu-email@universidad.edu
- 🐛 Issues: [GitHub Issues](https://github.com/tu-usuario/autoconocimiento-evaluacion/issues)

---

**⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub**
