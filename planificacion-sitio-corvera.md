# 📄 Documento de planificación para el sitio web del Consultorio Dra. Patricia Corvera

---

## 🧭 1. Objetivo general del sitio

Crear un sitio web estático profesional y atractivo para:

- Presentar a la Dra. Patricia Corvera como referente confiable en medicina estética, dermatología y pediatría.
- Comunicar con claridad los tratamientos y servicios ofrecidos.
- Facilitar el contacto, ubicación y solicitud de turnos.
- Generar confianza en potenciales pacientes a través de testimonios y una imagen cuidada.

---

## 👥 2. Público objetivo

- Mujeres de entre 20 y 60 años interesadas en tratamientos estéticos y cuidado de la piel.
- Padres/madres que buscan atención pediátrica confiable.
- Personas de toda identidad de género con interés en dermatología médica o estética.
- Pacientes actuales que desean obtener información o recomendar el consultorio.

---

## 🧱 3. Estructura del sitio (Sitemap)

```
/
├── Inicio (/)
├── Sobre la doctora (/sobre)
├── Servicios (/servicios)
│   ├── Medicina estética
│   ├── Dermatología clínica
│   └── Pediatría
├── Turnos y contacto (/contacto)
├── Preguntas frecuentes (/preguntas-frecuentes)
├── Testimonios (/testimonios)
└── Ubicación (/ubicacion)
```

---

## 🧩 4. Contenidos clave por sección

### 🔹 Inicio

- Frase destacada / lema.
- Imagen hero de la doctora o del consultorio.
- CTA: “Solicitá tu turno” / “Conocé nuestros tratamientos”.
- Vista previa de servicios destacados.
- Enlace a sección “Sobre la doctora”.
- Testimonios breves.
- Mapa con ubicación.
- Footer con contacto rápido y redes.

### 🔹 Sobre la doctora

- Foto profesional.
- Título universitario y matrícula.
- Especialidades (pediatría, dermatología, estética).
- Diplomaturas o certificaciones.
- Filosofía profesional y estilo de atención.
- CTA: “Ver tratamientos disponibles”.

### 🔹 Servicios

Separado en 3 grandes categorías:

1. **Medicina estética**
   - Botox
   - Ácido hialurónico
   - Peeling Hollywood
   - Luz pulsada (IPL)
   - Mesoterapia facial y corporal
2. **Dermatología**
   - Control de lunares
   - Acné, rosácea, psoriasis
   - Diagnóstico de manchas y lesiones
3. **Pediatría**
   - Controles de salud infantil
   - Asesoramiento nutricional
   - Derivaciones, vacunas

Cada servicio incluirá:
- Nombre y categoría.
- Breve descripción (qué es, para qué sirve).
- Imagen representativa.
- Frecuencia/tiempo estimado.
- Indicaciones / contraindicaciones breves (si aplica).

### 🔹 Turnos y contacto

- Horarios de atención.
- Botón para agendar turno (WhatsApp directo).
- Teléfono, email.
- Redes sociales (Instagram, TikTok, Facebook).

### 🔹 Preguntas frecuentes

- ¿Los tratamientos son dolorosos?
- ¿Cuánto tiempo duran los efectos del botox?
- ¿Se puede hacer IPL en verano?
- ¿Qué cuidados debo tener después de un peeling?
- ¿Desde qué edad puedo llevar a mi hijo a un control pediátrico?

### 🔹 Testimonios

- Frases breves de pacientes satisfechos (con consentimiento).
- Opcional: fotos o íconos decorativos.

### 🔹 Ubicación

- Dirección completa.
- Embed de Google Maps.
- Accesibilidad (colectivos cercanos, estacionamiento).
- Texto: “Nos encontramos en la ciudad de Avellaneda, fácil acceso desde CABA y zona sur.”

---

## 🧑‍🎨 5. Estilo visual y branding

- **Paleta de colores:**
  - Marrón: `#734E40`
  - Beis: `#E4BDA4`
  - Nude: `#FFEEE6`
  - Rosa Viejo: `#C6707D`

- **Tipografía sugerida:**
  - Títulos: Playfair Display, Lora
  - Texto: Open Sans, Montserrat, Inter

- **Estética visual:**
  - Minimalista, femenina, cálida.
  - Imágenes de alta calidad, propias.
  - Buen uso del espacio en blanco.

---

## ⚙️ 6. Tecnología y estructura de desarrollo

- **Framework:** Astro
- **CSS:** Tailwind CSS
- **Hosting:** Netlify o Vercel
- **Dominio:** A definir (.com.ar o .salud.ar)
- **Estructura modular:** componentes reutilizables
  - Header, Footer
  - Cards de servicio y testimonios
  - Layout general

---

## 🔎 7. Resolución de incertidumbres

### Precios

- ❌ No se mostrarán precios.
- El foco estará en el valor profesional y los beneficios, no en competir por precio.

### Promociones

- ❌ No se incluirán promociones.
- Se evita mantenimiento innecesario y se prioriza estabilidad del contenido.

### Redes sociales

- ✅ Se mostrarán de forma visible.
- Serán enlaces destacados en footer y posiblemente en otras secciones.

### Fotos

- ✅ Se utilizarán fotos propias del consultorio y la doctora.

### Idioma alternativo

- ❌ El sitio estará solo en español.

### Blog

- ❌ No se incluirá blog/tips para evitar carga de mantenimiento.

### Horarios

- ✅ Se mostrarán horarios de atención visibles.

### Certificaciones

- ✅ Se incluirán logos de certificaciones, títulos y sociedades médicas relevantes.

---

## 🛠️ 8. Tareas previas al desarrollo

- [ ] Redactar textos definitivos por sección
- [ ] Seleccionar y organizar fotos propias
- [ ] Confirmar horario de atención
- [ ] Validar enlaces y perfiles de redes sociales
- [ ] Registrar dominio
- [ ] Reunir logos de certificaciones