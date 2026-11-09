# Resumen del proyecto — Sitio web de Sergio Trigo

*Actualizado: 8 de noviembre de 2026*

## El proyecto

Sitio web de **marca personal de Sergio Trigo ("Checho")**, kinesiólogo deportivo en Santiago de Chile.

- **Dominio:** kinetraumadeportivo.cl
- **Instagram:** [@chechokine_](https://www.instagram.com/chechokine_/) ("Kine trauma deportivo")
- **Objetivo principal:** que el paciente agende lo más rápido posible.
- **Especialidad:** reintegro deportivo y lesiones de deportistas.
- **Técnicas:** terapia manual ortopédica (TMO) y fisioterapia invasiva (punción seca).
- **Público:** peleadores (boxeo, MMA, jiu-jitsu, muay thai), runners y gymbrats.
- **Dato real para usar en el sitio:** +100 pacientes (según su bio de Instagram).
- **Dirección de atención:** Av. Hernando de Aguirre 162, Oficina 301, Providencia, Región Metropolitana.
- **Primera evaluación:** 30 minutos.

## Lo que está hecho

### 1. Repositorio y publicación
- Repositorio en GitHub: [sofimujicac/checho](https://github.com/sofimujicac/checho).
- Publicado con GitHub Pages en **https://sofimujicac.github.io/checho/**.
- Cada cambio que se sube a la rama `main` se publica solo en 1–2 minutos.

### 2. Estudio de mercado
Guardado en [`Estudio de Mercado/estudio-de-mercado.md`](Estudio%20de%20Mercado/estudio-de-mercado.md). Incluye:

- **Categorización de Sergio:** marca personal de kinesiólogo independiente. La estrategia recomendada combina la cercanía de una marca personal, la conversión de las cadenas de fisioterapia y la transparencia de Doctoralia (precio y disponibilidad visibles).
- **Ranking de referentes** (máximo 3 por región):

| | 1° | 2° | 3° |
|---|---|---|---|
| Chile | Doctoralia.cl | Clínica MEDS | Clínica Alemana |
| Latinoamérica | Doctoralia México | Top Doctors México | Fleni (Argentina) |
| Estados Unidos | Athletico | HSS | Squat University |
| Europa | Pure Sports Medicine | Six Physio | Clínica CEMTRO |

- **Patient journey:** qué pregunta el paciente en cada etapa y cuántos clics le toma agendar en cada sitio.
- **UX/UI que funciona:** agenda en la primera pantalla, botón "Agendar" siempre visible, reseñas con números concretos, entrada por "¿qué te duele?" y WhatsApp.
- **SEO:** palabras clave para Chile ("kinesiólogo", no "fisioterapeuta"), plantilla de metadata y datos estructurados, y prioridad al SEO local (perfil de Google y Doctoralia).

### 3. Definiciones de marca y diseño
- **Frase principal**, inspirada en Pure Sports Medicine y adaptada a Chile: *"Atención de élite, para todos. No tienes que ser deportista profesional para que te traten como uno."*
- **Diferenciador:** *"No te doy el alta por calendario, te la doy cuando estás listo."* Es un reintegro por fases, con test de fuerza antes del alta.
- **Paleta de colores:** `#0A0F14` · `#0F3D3E` · `#2E6F73` · `#7FB3B8` · `#EADCC8` · `#C6601F`
- **Dirección visual:** editorial, con sensación de **confianza, calma y elegancia**. Que no se vea hecho con IA.
- ~~El color oscuro no debe ser el protagonista.~~ Actualizado el 8-nov: la base ahora es oscura ("Noche andina").
- Se reemplazó el modo claro/oscuro automático por una sola paleta oscura de marca (las versiones claras quedan en la herramienta Paleta).
- **Fotos:** de Sergio o de personas que se vean chilenas. Mientras no estén, se trabaja con mockups (bloques etiquetados que indican qué foto va en cada lugar).
- **Referencia de estilo:** [Kinera – Physiotherapy Clinic Website](https://www.behance.net/gallery/256512367/Kinera-Physiotherapy-Clinic-Website) (Behance). La imagen completa está en `kinera-diseno-web.jpg`.

### 4. Versión actual del sitio (`index.html`)
- **Estructura según el mockup en PDF** (`Mockup_web_Sergio_Trigo.pdf`): hero "Entrena sin dolor." → ¿Para quién es? (combate, runners, gymrats) → Tu primera evaluación (01 Evaluamos, 02 Tratamos, 03 Planificamos) → Tratamientos (kinesiología deportiva, punción seca, MEP, masaje deportivo) → Soy Sergio → Resultados reales → Plan de entrenamiento online → Preguntas frecuentes → Vuelve a entrenar sin dolor (agendar).
- **Estilo visual de Kinera**: palabras gigantes que se desvanecen (ahora más legibles y sin quedar tapadas), fotos grandes y tarjetas de vidrio.
- **Paleta base "Noche andina"**, solo con los 6 colores de la marca: fondo #0A0F14, paneles #0F3D3E y #2E6F73, texto #EADCC8, botones #C6601F y detalles #7FB3B8.
- **Marca:** "Sergio Trigo" en logo, título, footer y datos de Google. "Kine trauma deportivo" queda como descripción. El dominio kinetraumadeportivo.cl se mantiene.
- **Isotipo:** sello "ST." (fondo petróleo, letras arena, punto cobre). Nunca usar trigo (la planta) como logo.
- **Fotos de mockup** (Unsplash) con gente de aspecto latino y Santiago (atardecer y noche), en `img/mockups/`. La sección de evaluación usa una foto horizontal de boxeo con pared verde azulado.
- **Fluidez:** barra de progreso, índice de puntos al costado, bloques que aparecen al bajar, carrusel de testimonios, cinta de deportes y contador +100.
- **Menú** que resalta la sección visible (clic y scroll). En celular hay menú desplegable.
- **Herramienta "Paleta"** (abajo a la izquierda, al abrir el archivo en el computador o con `?paleta` en la URL): combina solo los 6 colores de la marca.
- Los textos entre [corchetes] y subrayados son datos pendientes de Sergio.

### 5. Material de Instagram recopilado
En la carpeta `img/` están la foto de perfil de Sergio y sus publicaciones propias: punción seca, condropatía rotuliana, disfunción patelofemoral, salto vertical y fuerza de agarre.

## Pendiente

**Datos que tiene que entregar Sergio:**
- WhatsApp real (hoy el sitio usa un número de prueba).
- Si atiende a domicilio, y horarios de atención.
- Precios de la primera sesión y de las sesiones siguientes.
- Descripción simple de MEP y detalles del plan online (para quién, duración, qué incluye).
- Formación, años de experiencia y número de registro en la Superintendencia de Salud.
- Fotos en buena calidad: retrato y fotos atendiendo pacientes.
- Testimonios reales, con permiso de los pacientes.

**Próximos pasos del sitio:**
- Revisar y aprobar el diseño (versión con fotos de mockup).
- Reemplazar los mockups por fotos reales.
- Subir la versión final a GitHub Pages.
- Configurar el dominio kinetraumadeportivo.cl.
- Crear el perfil de Google (Maps) y el perfil de Doctoralia.
