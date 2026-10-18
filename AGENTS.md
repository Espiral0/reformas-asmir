# Web de Reformas [Nombre]

> Este archivo lo leen los agentes (como Antigravity) al empezar a trabajar en esta carpeta.

## Qué es
Web de una sola página para una empresa de reformas (cocinas, baños, reformas integrales, suelos, instalaciones y locales).
Objetivo principal: que el visitante pida presupuesto (formulario, teléfono o WhatsApp).
Secciones: portada, ventajas, servicios ("Qué hacemos"), "Cómo trabajamos", presupuesto/contacto y pie, más un botón flotante de WhatsApp.

## Pendiente de personalizar
- Datos marcados entre corchetes: `[Nombre]`, `[Tu ciudad]`.
- Teléfono `600 000 000` / `34600000000` y email `info@tuempresa.com` son de ejemplo.
- La imagen de la portada es un hueco: hay que poner fotos reales de obras.
- El formulario no envía mensajes todavía.

## Es una plantilla
Esta web es una plantilla genérica para reutilizar con distintas empresas de reformas.
Cuando te pida personalizarla para un cliente:
1. Sustituye todos los datos de ejemplo (`[Nombre]`, `[Tu ciudad]`, teléfono, WhatsApp, email) en `index.html`, también el `<title>` y el pie.
2. Ajusta servicios, textos y colores (`:root` en `styles.css`) a lo que te diga.
3. Si hay fotos en la carpeta, colócalas en la portada.
4. Revisa que no quede ningún texto de ejemplo y resume qué has cambiado.

## Tecnologías
- HTML, CSS y JavaScript puros, sin frameworks ni instalaciones.

## Estructura
- `index.html`: contenido y estructura de la página
- `styles.css`: diseño (los colores principales están en `:root`, al principio)
- `script.js`: año automático del pie y aviso del formulario
- `README.md`: descripción del proyecto para personas
- `CLAUDE.md`: instrucciones para Claude Code
- `AGENTS.md`: las mismas instrucciones para Antigravity (si cambias uno, cambia también el otro)

## Cómo verla
- Haz doble clic en `index.html` para abrirla en el navegador.
- No necesita servidor ni comandos.

## Normas
- Mantén la web simple: nada de frameworks ni dependencias, salvo que lo pida.
- Escribe los comentarios del código y los textos en español.
- Explica los cambios de forma sencilla: soy principiante.
- Pregunta antes de borrar archivos.
- No inventes opiniones de clientes, cifras (años de experiencia, obras hechas) ni certificados: usa solo datos reales que yo dé.
- Tono cercano y claro, pensado para particulares; cada sección debe llevar a pedir presupuesto.
- El formulario de contacto aún no envía mensajes; avisa antes de conectarlo a un servicio externo.
