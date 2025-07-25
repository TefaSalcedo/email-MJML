# 🌟 Rinconcito Digital de Estefania - Email en MJML

Este proyecto es un ejemplo de cómo crear un **boletín informativo HTML** usando el framework **MJML** (Mailjet Markup Language). MJML facilita la creación de correos electrónicos responsivos con una sintaxis simple y legible.

## 🛠 Herramientas utilizadas

- **MJML**: para estructurar el diseño del correo.
- **Brevo (antes Sendinblue)**: para enviar la campaña.
- **Giphy + Unsplash + Pinterest**: para enriquecer visualmente el boletín.

---

# 💌 Plantilla MJML - Rinconcito Digital de Estefania

Este es un ejemplo de plantilla de correo electrónico diseñada con **MJML** y pensada para usarse con **Brevo** (antes Sendinblue). La estructura es visual, amigable y responsiva.

---

## 📄 Estructura general

```mjml
<mjml>
  <mj-body>
    <!-- Aquí van los bloques del contenido -->
  </mj-body>
</mjml>


<mj-hero mode="fixed-height" height="auto" background-color="#edc7f6ff" padding="0">
  <mj-text> 🌟 Rinconcito Digital de Estefania 🌟 </mj-text>
</mj-hero>


<mj-section background-color="#ffffff">
  <mj-column>
    <mj-image src="...jpg" width="200px" />
  </mj-column>
</mj-section>

<mj-text> ¡Hola Estefania! 👋 </mj-text>
<mj-button href="https://brevo.com"> Ver mi campaña </mj-button>

<mj-section>
  <mj-group>
    <mj-column>Texto</mj-column>
    <mj-column><mj-image src="...gif" /></mj-column>
  </mj-group>
</mj-section>

<mj-section>
  <mj-group>
    <mj-column>Texto</mj-column>
    <mj-column><mj-image src="...gif" /></mj-column>
  </mj-group>
</mj-section>

<mj-section
  background-url="https://images.unsplash.com/photo-1503..."
  background-size="cover"
>
  <mj-column>
    <mj-text>Una postal desde mi mundo 🌍</mj-text>
  </mj-column>
</mj-section>

<mj-text>Enviado con 💜 por Estefania Salcedo</mj-text>
<mj-social>
  <mj-social-element href="...">Facebook</mj-social-element>
  ...
</mj-social>

