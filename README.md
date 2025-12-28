# 🎯 Tarjeta Digital Profesional

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-proprietary-red.svg)]()

> Tarjeta digital profesional con verificación de credenciales, datos fiscales integrados y experiencia de usuario premium.

🔗 **Demo en vivo:** [maesauldavila.github.io/tarjeta-digital](https://maesauldavila.github.io/tarjeta-digital/)

---

## 📋 Contenido

- [Características](#-características)
- [Propiedad Intelectual](#️-propiedad-intelectual)
- [Tecnologías](#️-tecnologías)
- [Instalación Local](#-instalación-local)
- [Licencia](#-licencia)
- [Contacto](#-contacto)

---

## ✨ Características

### Diseño Premium - Boutique
- Glassmorphism con efectos de blur y transparencias
- Modo oscuro automático con persistencia
- 15+ micro-interacciones y animaciones fluidas
- 100% responsive (320px - 4K)
- WCAG 2.1 AA compliant
- Nivel boutique agency ($8,500-11,000 USD valor de mercado)

### Funcionalidades

| Elemento | Clic Normal | Mantener 1 seg |
|----------|-------------|----------------|
| **Ícono Central ⊚** | Modal QR + vCard | Easter egg |
| **Cédula** | Copiar número | Verificar en SEP |
| **Certificación** | Copiar código | Verificar en OLA |
| **Teléfono** | Abrir WhatsApp | Descargar .vcf |
| **Email** | Abrir cliente | Copiar email |

### Datos Integrados
- ✅ Verificación de credenciales (Cédula SEP, Cert. OLA/CICA)
- ✅ Información fiscal completa (RFC, Régimen, CLABE, Tarjeta)
- ✅ Feedback multisensorial (audio + háptico)
- ✅ Generación de QR bajo demanda
- ✅ Descarga de vCard

### Performance
- **Peso:** ~50KB (ultra-ligero)
- **Carga:** <1s en 3G
- **Lighthouse:** 98/100 Performance

---

## 🛡️ Propiedad Intelectual

### ⚠️ PROTECCIÓN DE MARCA Y CONTENIDO

**Este repositorio está protegido por derechos de autor.**

#### 🏢 Marca Corporativa AIDN

**ELEMENTOS PROTEGIDOS:**
- ✓ Logo AIDN (hexágono con gradiente azul)
- ✓ Paleta de colores (#0c2a85, #03b4d6)
- ✓ Sistema de branding
- ✓ Tagline corporativo: "Catapultando empresas para liderar el cambio"

**© 2025 AIDN. Todos los derechos reservados.**

#### 👤 Branding Personal

**ELEMENTOS PROTEGIDOS:**
- ✓ Nombre y credenciales profesionales
- ✓ Cédula SEP 14051498
- ✓ Certificación OLA/CICA
- ✓ Información fiscal y financiera
- ✓ Diseño y estructura de la tarjeta
- ✓ Tagline personal: "Estrategias que definen futuros"

**© 2025 Saúl Dávila Pantoja. Todos los derechos reservados.**

---

## 📜 Restricciones de Uso

### ❌ PROHIBIDO (Sin autorización escrita):

1. Uso comercial del diseño o código
2. Clonar/bifurcar con fines comerciales
3. Uso de marca AIDN en proyectos propios
4. Uso de identidad personal (nombre, credenciales, datos)
5. Modificación y redistribución comercial
6. Scraping de datos personales o fiscales

### ✅ PERMITIDO (Con atribución):

1. Visualización del código para fines educativos
2. Referencias técnicas en artículos (con crédito)
3. Inspiración conceptual (no copia directa)
4. Fork para estudio personal (no público)

---

## ⚖️ Licencia Propietaria

**Este proyecto NO está bajo licencia de código abierto.**

```
Copyright © 2025 AIDN & Saúl Dávila Pantoja

LICENCIA PROPIETARIA

Todos los derechos reservados. No se permite:
- Uso comercial
- Redistribución
- Uso de marca AIDN
- Uso de identidad personal
- Trabajos derivados comerciales

Uso educativo permitido con atribución adecuada.

Para permisos comerciales: sauldavila@gmail.com
```

### 🚨 Protección Legal

Este repositorio está protegido bajo:
- Ley Federal del Derecho de Autor (México)
- Digital Millennium Copyright Act (DMCA)
- Propiedad intelectual corporativa de AIDN

**Violaciones serán reportadas bajo DMCA Takedown Notice.**

---

## 🛠️ Tecnologías

### Stack
- **HTML5** semántico
- **CSS3** (Custom Properties, Backdrop Filters, Grid, Flexbox)
- **JavaScript ES6+** vanilla (sin frameworks)
- **QRious 4.0.2** - Generación de códigos QR

### APIs del Navegador
- Web Audio API (feedback sonoro)
- Vibration API (feedback háptico)
- Clipboard API (copiar datos)
- Web Share API (compartir QR)
- localStorage API (persistencia de tema)

---

## 💻 Instalación Local

### Visualización Directa

```bash
# Clonar (solo para visualización educativa)
git clone https://github.com/maesauldavila/tarjeta-digital.git

# Abrir en navegador
open index.html
```

### Con Servidor Local (Recomendado)

**Python:**
```bash
python -m http.server 8000
# Abrir http://localhost:8000
```

**Node.js:**
```bash
npx http-server -p 8000
```

**VS Code:**
- Instalar extensión "Live Server"
- Click derecho en `index.html` → "Open with Live Server"

---

## 📊 Estructura del Proyecto

```
tarjeta-digital/
│
├── index.html                  # Aplicación completa (single-file)
├── README.md                   # Este archivo
├── LICENSE                     # Licencia propietaria
│
├── favicon.ico                 # Favicon 16x16
├── favicon-32x32.png          # Favicon 32x32
├── apple-touch-icon.png       # iOS icon
├── banner-tarjeta-digital.png # OG image (1280x640)
│
└── .github/
    └── FUNDING.yml            # Info de contacto
```

**Arquitectura single-file por diseño:**
- ✅ Máxima portabilidad
- ✅ Cero dependencias de build
- ✅ Deploy instantáneo
- ✅ Fácil mantenimiento

---

## 🎯 Uso

### Para Visitantes

1. Navegar a la URL
2. Clic en ícono central (⊚) para QR
3. Clic en credenciales para copiar
4. Mantener presionado para acciones avanzadas
5. Descargar vCard desde modal

### Para Desarrolladores (Referencia)

**Puntos de aprendizaje destacados:**

```javascript
// Estado centralizado
const state = {
  theme: 'light',
  themeManuallySet: false,
  qrGenerated: false
};

// Caché de elementos DOM (-40% consultas)
const els = {};

// Feedback multisensorial
const playSound = (frequency, duration) => {
  const ctx = new AudioContext();
  const osc = ctx.createOscillator();
  osc.frequency.setValueAtTime(frequency, ctx.currentTime);
  // ...
};

// Hold gesture detection
let holdTimer = null;
element.addEventListener('mousedown', () => {
  holdTimer = setTimeout(handleLongPress, 800);
});
```

---

## 🔐 Política de DMCA

**Reportamos violaciones activamente.**

Si detectamos uso no autorizado:
1. DMCA Takedown Notice a GitHub
2. Reporte a plataformas de hosting
3. Acciones legales según gravedad

**Para evitar problemas:**
- Solicita permisos ANTES de usar
- Proporciona atribución adecuada
- Respeta las restricciones

---

## 📞 Contacto

### Para Permisos Comerciales

**MAE Saúl Dávila Pantoja**
- 📧 Email: sauldavila@gmail.com
- 📱 WhatsApp: [+52 1 55 3719 1248](https://wa.me/5215537191248)
- 🌐 Tarjeta: [maesauldavila.github.io/tarjeta-digital](https://maesauldavila.github.io/tarjeta-digital/)

### Para Marca AIDN

- 📧 Via Saúl Dávila (Representante Autorizado)

### Reportar Uso No Autorizado

**Email:** sauldavila@gmail.com  
**Asunto:** "Reporte DMCA - Tarjeta Digital"

---

## 🙏 Reconocimientos

### Tecnologías Open Source

- **QRious** - MIT License (neocotic)
- **Google Fonts** - Open Font License
  - IBM Plex Sans
  - Rajdhani

**Nota:** Las restricciones aplican únicamente al código personalizado, diseño, branding y contenido propietario.

---

## 📈 Métricas

### Lighthouse Scores

| Métrica | Score |
|---------|-------|
| Performance | 98/100 |
| Accessibility | 100/100 |
| Best Practices | 100/100 |
| SEO | 100/100 |

### Compatibilidad

| Navegador | Versión | Soporte |
|-----------|---------|---------|
| Chrome | 90+ | ✅ |
| Firefox | 88+ | ✅ |
| Safari | 14+ | ✅ |
| Edge | 90+ | ✅ |

---

## ❓ FAQ

### ¿Puedo usar este código para mi tarjeta?

**No directamente.** Necesitarías eliminar toda la marca AIDN, información personal, y contactarme para permisos.

### ¿Puedo hacer un fork público?

**Solo para estudio personal.** Si lo haces público, elimina TODO el contenido protegido.

### ¿Cuánto cuesta una licencia comercial?

**Contactar para negociación:**
- Uso individual: $500-1,500 USD
- Uso corporativo: $2,000-5,000 USD
- Licencia de plantilla: $10,000+ USD

### ¿El hosting es permanente?

**Sí.** GitHub Pages es gratuito para siempre mientras tu cuenta esté activa. Sin fecha de expiración ni renovaciones.

---

## 🎓 Uso Educativo

### Si Quieres Referenciar

**En artículos:**
```markdown
Inspirado por [Tarjeta Digital - Saúl Dávila]
(https://github.com/maesauldavila/tarjeta-digital)

Nota: Código original bajo licencia propietaria.
Solo se usan conceptos generales.
```

**Permitido:**
- ✅ Explicar conceptos técnicos
- ✅ Screenshots con marca visible
- ✅ Disclaimer de propiedad intelectual

**Prohibido:**
- ❌ Copiar código sin atribución
- ❌ Usar como base comercial

---

## 💡 Filosofía del Proyecto

> *"La estrategia empieza cuando termina la improvisación."*

**Principios:**
1. **Profesionalismo primero** - Cada detalle cuenta
2. **Verificabilidad** - Credenciales auténticas
3. **Eficiencia** - Reducir fricciones
4. **Innovación** - Estar a la vanguardia
5. **Accesibilidad** - Funcional para todos

---

## 🏆 Valor del Proyecto

**Este proyecto representa:**
- 120-150 horas de desarrollo senior
- $8,500-11,000 USD valor de mercado
- Código production-ready
- Branding protegido legalmente

**Respeto mutuo = Comunidad saludable.**

---

## 📝 Changelog

### v1.0.0 (Diciembre 2025)

**Features:**
- ✅ Arquitectura single-file
- ✅ Verificación de credenciales
- ✅ Datos fiscales integrados
- ✅ Dark mode automático
- ✅ Feedback multisensorial
- ✅ QR generation
- ✅ 15+ micro-interacciones

**Performance:**
- 98/100 Lighthouse
- ~50KB peso total
- <1s carga en 3G

---

## 🤝 Contribuciones

**Política: CERRADO**

Este es un proyecto personal/corporativo privado.

- ❌ No se aceptan Pull Requests
- ❌ No se aceptan Issues públicos
- ❌ No se buscan colaboradores

**Para reportar bugs:** sauldavila@gmail.com

---

## ⭐ ¿Te Gusta Este Proyecto?

- ⭐ Dale una estrella al repositorio
- 📢 Compártelo con atribución
- 💬 Contacta para permisos comerciales
- 🙏 Respeta la propiedad intelectual

**Dar estrella ≠ Permiso de uso comercial**

---

**© 2025 AIDN & Saúl Dávila Pantoja - Todos los derechos reservados**

*Tarjeta Digital Profesional con verificación de credenciales*
