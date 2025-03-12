# 🎯 Generador de Preguntas GIFT para Oposiciones

Plataforma web interactiva para la generación automática de preguntas tipo test en formato GIFT, especialmente diseñada para oposiciones y exámenes oficiales en el ámbito legal y militar.

## 🚀 Características Principales

### 📝 Entrada de Contenido
- **Carga de Documentos**:
  - Formatos soportados: PDF, TXT, Markdown
  - Procesamiento automático del contenido
  - Vista previa con opción de expandir/contraer
  - Función de copiado rápido

- **Editor de Texto**:
  - Entrada manual de contenido
  - Soporte para formato Markdown
  - Interfaz intuitiva tipo editor

### 🤖 Integración con IA
- **Múltiples Proveedores**:
  - Anthropic (Claude)
  - Deepseek
  - Google (Gemini)
  - xAI (Grok)
  - Alibaba (Qwen)
  - OpenAI (GPT)

- **Configuración Personalizada**:
  - Selección de modelo
  - Ajuste de temperatura
  - Control de tokens máximos
  - Prompt personalizable

### 📋 Generación de Preguntas
- **Tipos de Preguntas**:
  - Espacios en blanco (5%)
  - Preguntas textuales (75%)
  - Identificación de incorrectas (10%)
  - "Ninguna es correcta" (10%)

- **Niveles de Dificultad**:
  - Difícil
  - Muy difícil
  - Extremadamente difícil

### 📚 Formato GIFT Mejorado
- **Estructura de Preguntas**:
  - Título y referencia normativa
  - Pregunta principal
  - 4 opciones de respuesta
  - Retroalimentación detallada

- **Retroalimentación Enriquecida**:
  - Fundamento conceptual
  - Relevancia operativa
  - Relaciones clave
  - Aplicación práctica
  - Reglas mnemotécnicas

### 💾 Gestión de Contenido
- **Historial**:
  - Registro de preguntas generadas
  - Marca de tiempo
  - Opción de reutilización
  - Evita duplicados

- **Exportación**:
  - Descarga en formato GIFT
  - Copia al portapapeles
  - Compatible con Moodle

## 🛠️ Tecnologías Utilizadas

### Frontend
- Next.js
- React
- TailwindCSS
- TypeScript

### Backend
- Node.js
- Express
- API REST

### Base de Datos
- MongoDB/PostgreSQL (pendiente de implementar)

## 📦 Instalación

1. Clonar el repositorio:
```bash
git clone [URL_DEL_REPOSITORIO]
```

2. Instalar dependencias:
```bash
npm install
```

3. Configurar variables de entorno:
```bash
cp .env.example .env
```

4. Iniciar el servidor de desarrollo:
```bash
npm run dev
```

## 🔑 Configuración de API Keys

Para utilizar los diferentes modelos de IA, necesitas configurar las siguientes API keys:

- OPENAI_API_KEY
- ANTHROPIC_API_KEY
- GOOGLE_API_KEY
- DEEPSEEK_API_KEY
- XAI_API_KEY
- ALIBABA_API_KEY

## 🎯 Público Objetivo

- Opositores y estudiantes
- Educadores y formadores
- Profesionales del ámbito legal/militar
- Creadores de contenido educativo

## 🔄 Flujo de Trabajo

1. **Inicio**: Selección de modo de entrada (archivo/texto)
2. **Configuración**: Selección de modelo y parámetros
3. **Procesamiento**: Análisis del contenido
4. **Generación**: Creación de preguntas
5. **Revisión**: Verificación y ajuste
6. **Exportación**: Descarga o copia

## 🌟 Características en Desarrollo

- [ ] Integración con LMS
- [ ] Sistema de usuarios
- [ ] Base de datos de preguntas
- [ ] API pública
- [ ] Más formatos de exportación

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor, lee [CONTRIBUTING.md](CONTRIBUTING.md) para detalles sobre nuestro código de conducta y el proceso para enviarnos pull requests.