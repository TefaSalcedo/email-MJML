# 🌟 Rinconcito Digital de Estefania - Email en MJML

Este proyecto es un ejemplo de cómo crear un **boletín informativo HTML** usando el framework **MJML** (Mailjet Markup Language). MJML facilita la creación de correos electrónicos responsivos con una sintaxis simple y legible.

## 🛠 Herramientas utilizadas

- **MJML**: para estructurar el diseño del correo.
- **Brevo (antes Sendinblue)**: para enviar la campaña.
- **Giphy + Unsplash + Pinterest**: para enriquecer visualmente el boletín.

---

## 📄 Estructura del archivo MJML

```xml
<mjml>
  <mj-body>
    ...
  </mj-body>
</mjml>

---
## ✨ Componentes y qué hacen
### 1. mj-hero
---
<mj-hero mode="fixed-height" height="auto" background-color="#edc7f6ff" padding="0">
  <mj-text>...</mj-text>
</mj-hero>
---
### 2. mj-section + mj-column + mj-image
---
<mj-section background-color="#ffffff">
  <mj-column>
    <mj-image src="..." />
  </mj-column>
</mj-section>
---
### 3. Texto de bienvenida y botón
---
<mj-text> ¡Hola Estefania! 👋 </mj-text>
<mj-button href="https://brevo.com"> Ver mi campaña </mj-button>
---
###  4. mj-group para alinear texto e imagen (2 columnas)
---
<mj-group>
  <mj-column>Texto</mj-column>
  <mj-column>Gif</mj-column>
</mj-group>
---
### 5. Sección con imagen de fondo (background-url)
---
<mj-section background-url="..." background-size="cover">
  <mj-column>
    <mj-text>Una postal desde mi mundo 🌍</mj-text>
  </mj-column>
</mj-section>
---
### 6. Pie de página con info y redes sociales
---
<mj-text>Enviado con 💜 por Estefania Salcedo</mj-text>
<mj-social>
  <mj-social-element href="...">Facebook</mj-social-element>
  ...
</mj-social>

