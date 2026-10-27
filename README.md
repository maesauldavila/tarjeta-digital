# Tarjeta digital · MAE Saúl Dávila Pantoja

[![Estado](https://img.shields.io/badge/estado-activo-success.svg)]()
[![Licencia](https://img.shields.io/badge/licencia-propietaria-red.svg)]()
[![Versión](https://img.shields.io/badge/versión-2026.10-blue.svg)]()

> Tarjeta digital profesional de MAE Saúl Dávila Pantoja, Consultor Estratégico y fundador de AIDN Strategic Consulting: contacto en un toque, verificación de la cédula profesional, código QR con tarjeta de contacto y datos fiscales y de pago a la mano de clientes.

**Tarjeta en vivo:** [maesauldavila.github.io/tarjeta-digital](https://maesauldavila.github.io/tarjeta-digital/)

---

## Contenido

- [Qué es](#qué-es)
- [Cómo se usa](#cómo-se-usa)
- [Datos personales publicados](#datos-personales-publicados)
- [Propiedad intelectual](#propiedad-intelectual)
- [Restricciones de uso](#restricciones-de-uso)
- [Licencia propietaria](#licencia-propietaria)
- [Alcance de la protección y elementos de terceros](#alcance-de-la-protección-y-elementos-de-terceros)
- [Aspectos técnicos](#aspectos-técnicos)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Preguntas frecuentes](#preguntas-frecuentes)
- [Cómo reportar un uso no autorizado](#cómo-reportar-un-uso-no-autorizado)
- [Contribuciones](#contribuciones)
- [Contacto](#contacto)
- [Historial de cambios](#historial-de-cambios)

---

## Qué es

Una tarjeta de presentación digital de archivo único (HTML, CSS y JavaScript) pensada para compartirse por WhatsApp, código QR o enlace. Reúne en una sola pantalla:

- **Identidad profesional:** nombre, título «Consultor Estratégico · Planeación y dirección empresarial» y cédula profesional verificable.
- **Contacto directo:** WhatsApp, correo electrónico y sitio web de AIDN.
- **Tarjeta de contacto (vCard):** descargable y en código QR.
- **Datos fiscales y de pago** para clientes, copiables con un toque.
- **Tema claro y oscuro** y retroalimentación sonora y háptica discreta.

---

## Cómo se usa

Cada elemento responde a un **toque** y, en la mayoría, a una **pulsación sostenida** (aproximadamente 0.8 segundos).

| Elemento | Toque | Mantener presionado |
|----------|-------|---------------------|
| **Logotipo AIDN** | Prepara la acción | Doble toque: abre aidnstrategic.com |
| **Ícono central ⊚** | Abre el modal con QR y datos | Muestra la frase oculta de AIDN |
| **Cédula** | Copia el número | Abre la verificación en la SEP |
| **Teléfono** | Abre WhatsApp | Descarga la tarjeta de contacto (.vcf) |
| **Correo electrónico** | Abre el cliente de correo | Copia la dirección |
| **Sitio web** | Abre aidnstrategic.com | Copia la URL |

**Modal del código QR:**

- **Tarjeta de contacto:** descargar el QR, compartirlo y copiar la vCard.
- **Información fiscal:** copiar el RFC, copiar el régimen y verificar en el SAT.
- **Información de pagos:** copiar los datos de pago de las cuentas indicadas.

**Atajos:** `Esc` cierra el modal y `Ctrl + Alt + T` cambia el tema.

---

## Datos personales publicados

La tarjeta muestra de forma deliberada datos de contacto, la cédula profesional, información fiscal y datos de pago, para que clientes y contactos profesionales puedan usarlos. Por eso:

- Esos datos son **personales y se publican con un fin específico**: contacto, verificación profesional y pago de servicios a AIDN.
- **Está prohibido** extraerlos de forma automatizada, recopilarlos, venderlos, incorporarlos a bases de datos o usarlos para suplantar la identidad de su titular, solicitar pagos en su nombre o cualquier fin distinto.
- La cédula puede verificarse en el portal oficial de la SEP y el RFC en el validador del SAT.
- Para confirmar cualquier dato de pago antes de transferir, usa los canales de contacto de este documento.

---

## Propiedad intelectual

**Este repositorio está protegido por derechos de autor.**

### Marca de AIDN

- Logotipo hexagonal de AIDN y su variante animada
- Denominación «AIDN Strategic Consulting»
- Sistema de identidad: paleta, tipografía y componentes
- Lema: «Diseñamos la estructura estratégica para un crecimiento sostenible»

**© 2026 AIDN Strategic Consulting. Todos los derechos reservados.**

### Identidad y autoría personal

- Nombre, título profesional y datos de identificación
- Lema personal: «Estrategias que definen futuros»
- Frase oculta de la tarjeta
- Diseño, código, sistema de interacción (toque y pulsación sostenida, retroalimentación sonora y háptica) y textos

**© 2026 MAE Saúl Dávila Pantoja. Todos los derechos reservados.**

---

## Restricciones de uso

### Prohibido sin autorización escrita

1. Uso comercial del diseño, el código o los textos.
2. Clonar o bifurcar con fines comerciales.
3. Usar la marca o el logotipo de AIDN en proyectos propios o de terceros.
4. Usar la identidad personal: nombre, cédula, datos fiscales, de contacto o de pago.
5. Suplantar al titular o presentarse como su representante.
6. Modificar y redistribuir con fines comerciales.
7. Extracción automatizada de los datos personales, fiscales o de pago.
8. Eliminar o alterar avisos de derechos de autor.

### Permitido

1. Abrir, usar y compartir la tarjeta mediante su enlace oficial o su código QR.
2. Consultar el código con fines educativos y de aprendizaje personal.
3. Citarlo en artículos o tutoriales, con atribución.
4. Tomar ideas generales de interacción, sin copiar el código ni el diseño.

**Atribución requerida:**

```
Tarjeta digital de MAE Saúl Dávila Pantoja · AIDN Strategic Consulting
https://maesauldavila.github.io/tarjeta-digital/
Obra bajo licencia propietaria. Uso de referencia únicamente.
```

---

## Licencia propietaria

**Este proyecto no está bajo una licencia de código abierto.**

```
Copyright © 2026 AIDN Strategic Consulting y Saúl Dávila Pantoja

LICENCIA PROPIETARIA · TARJETA DIGITAL

Todos los derechos reservados. Sin autorización escrita no se permite:
- Uso comercial
- Redistribución o clonación
- Uso de la marca AIDN
- Uso de la identidad personal o de los datos publicados
- Extracción automatizada de datos
- Obras derivadas con fines comerciales

Se permiten el uso normal de la tarjeta y la consulta educativa con atribución.

Permisos comerciales: sauldavila@aidnstrategic.com
```

El acceso, la visualización o el uso de este proyecto implica la aceptación de estos términos.

---

## Alcance de la protección y elementos de terceros

- **Sí se protege** la expresión concreta: código, diseño, textos, selección y organización de contenidos, y la combinación de gestos con retroalimentación que define la experiencia.
- **No se reclaman derechos** sobre técnicas y estándares generales (por ejemplo, el formato vCard, los códigos QR, las interfaces de copiado al portapapeles o la detección de pulsación sostenida).
- **Plataforma:** GitHub permite, según sus propios términos, ver y bifurcar los repositorios públicos dentro de la plataforma. Eso no otorga una licencia de uso fuera de lo que se indica aquí.
- **Visibilidad del código:** la tarjeta es una página web; el navegador recibe todo su código. Verlo no equivale a una licencia para copiarlo.
- **Componentes de terceros:**
  - **QRious 4.0.2** (generación de códigos QR), licencia MIT, de neocotic. Se carga desde cdnjs.
  - **Google Fonts** (IBM Plex Sans, IBM Plex Mono y Rajdhani), con licencia de fuente abierta.

Las restricciones de este documento aplican al código propio, el diseño, la marca y el contenido.

---

## Aspectos técnicos

- **Arquitectura:** archivo único (`index.html`) con CSS y JavaScript en línea, sin proceso de compilación.
- **Lenguajes:** HTML5, CSS3 (propiedades personalizadas, filtros de fondo, cuadrícula y flexbox) y JavaScript moderno sin *frameworks*.
- **APIs del navegador:** Web Audio (sonido), Vibration (háptica), Clipboard (copiado), Web Share (compartir el QR como imagen) y `localStorage` (preferencia de tema).
- **Tema:** claro y oscuro, con detección automática y preferencia manual guardada en el navegador.
- **Adaptable:** diseño responsivo para teléfonos, tabletas y escritorio.
- **Accesibilidad:** botones con etiquetas, foco visible, objetivos táctiles de al menos 44 px y modal con atributos de diálogo.
- **Metadatos:** Open Graph y Twitter Cards para la vista previa en WhatsApp y redes.
- **Dependencias externas en ejecución:** QRious (cdnjs) y Google Fonts.
- **Navegadores:** versiones actuales de Chrome, Edge, Firefox y Safari.

### Privacidad de la propia página

La tarjeta no usa *cookies* propias, analítica ni publicidad. Solo guarda en el navegador de quien la visita la preferencia de tema. El código QR se genera en el dispositivo; no se envía a ningún servidor. Las fuentes y la biblioteca QR las sirven terceros, que pueden recibir datos de la conexión, como la dirección IP.

---

## Estructura del proyecto

```
tarjeta-digital/
│
├── index.html              # Tarjeta completa (archivo único)
├── README.md               # Este documento
├── LICENSE                 # Licencia propietaria
│
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png    # Ícono para iOS
└── banner-tarjeta.png      # Imagen Open Graph (1280×640)
```

---

## Preguntas frecuentes

### ¿Puedo usar este código para mi propia tarjeta?

No directamente. Tendrías que retirar toda la marca AIDN y toda la información personal, y solicitar autorización por escrito para usar el código y el diseño.

### ¿Puedo hacer un fork?

GitHub permite bifurcar repositorios públicos dentro de la plataforma. Un fork es solo para estudio personal; si lo haces público, debes eliminar todo el contenido protegido: marca, identidad y datos personales.

### ¿Puedo compartir mi tarjeta con el código QR o el enlace?

Sí. Está pensada para compartirse. Lo que no se permite es copiar o reutilizar su código, su diseño o sus datos.

### ¿Cómo verifico la cédula profesional?

Mantén presionada la cédula en la tarjeta para abrir el portal de verificación de la SEP, o consulta el número directamente en el portal oficial.

### ¿Puedo usar los datos de pago o fiscales para otra cosa?

No. Están publicados para clientes de AIDN y contactos profesionales. Antes de transferir, confirma el dato por un canal de contacto oficial.

### ¿Cuánto cuesta una licencia comercial?

Depende del uso y del alcance. Escribe a sauldavila@aidnstrategic.com para una propuesta.

---

## Cómo reportar un uso no autorizado

Escribe a **sauldavila@aidnstrategic.com** con el asunto «Reporte de uso indebido · Tarjeta digital» e incluye:

- la dirección (URL) donde aparece el uso,
- evidencia (capturas de pantalla o archivos) y
- una breve descripción de lo que se reproduce.

**Procedimiento ante un uso no autorizado:**

1. Notificación directa al infractor, con un plazo para retirar el contenido.
2. Notificación de retiro (DMCA) a GitHub o aviso a la plataforma de alojamiento.
3. Evaluación de las acciones legales que correspondan.

**Suplantación o uso de los datos de pago:** si recibes una solicitud de pago que dice venir de AIDN o de su titular y no coincide con los canales de este documento, no transfieras. Repórtala al correo anterior.

---

## Contribuciones

**Política: cerrado.** Este es un proyecto personal y corporativo.

- No se aceptan *pull requests*.
- No se aceptan *issues* públicos.
- No se buscan colaboradores.

Para reportar un error, escribe a sauldavila@aidnstrategic.com.

---

## Contacto

**MAE Saúl Dávila Pantoja** · Consultor Estratégico · Fundador de AIDN Strategic Consulting

- WhatsApp: [+52 55 3719 1248](https://wa.me/5215537191248)
- Correo electrónico: sauldavila@aidnstrategic.com
- Sitio web: [aidnstrategic.com](https://aidnstrategic.com)
- Tarjeta: [maesauldavila.github.io/tarjeta-digital](https://maesauldavila.github.io/tarjeta-digital/)

**Marca AIDN y permisos comerciales:** sauldavila@aidnstrategic.com

---

## Historial de cambios

### 2026.10 (octubre de 2026)

- Tarjeta renovada con el título «Consultor Estratégico · Planeación y dirección empresarial» y el lema corporativo vigente.
- Modal con tres secciones: tarjeta de contacto, información fiscal e información de pagos.
- Doble toque en el logotipo para abrir aidnstrategic.com y frase oculta en el ícono central.
- README reescrito: datos personales publicados, restricciones contra la extracción y la suplantación, alcance de la protección y elementos de terceros.

### Versión inicial (diciembre de 2025)

- Arquitectura de archivo único, tema claro y oscuro, QR bajo demanda y retroalimentación sonora y háptica.

---

**© 2026 AIDN Strategic Consulting y Saúl Dávila Pantoja · Todos los derechos reservados**

**Última actualización:** octubre de 2026 · **Versión del documento:** 2026.10 · **Mantenedor:** MAE Saúl Dávila Pantoja
