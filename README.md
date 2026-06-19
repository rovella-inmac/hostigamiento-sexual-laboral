# Hostigamiento Sexual Laboral — Presentación interactiva

Capacitación interna de sensibilización para **Consorcio Rovella Inmac**.
Presentación HTML autónoma (un solo archivo + recursos), en formato 16:9, con narración por diapositiva, pensada para exposición presencial y como video corporativo.

---

## 📁 Estructura de archivos

Para que la presentación funcione, estos elementos **deben mantenerse juntos** en la misma carpeta:

```
HOSTIGAMIENTO SEXUAL LABORAL/
├── index.html                     ← Presentación (abrir este archivo)
├── img/
│   ├── PNG__HORIZONTAL SIN SLOGAN.png   ← Logo para fondos claros
│   └── PNG__NEGATIVO PARCIAL.png        ← Logo para fondos oscuros
└── audio/
    ├── audio1.mp3 … audio9.mp3    ← Narración (1 por lámina)
    └── orden_audios.txt           ← Mapa lámina ↔ audio
```

> ⚠️ Si mueves o compartes la presentación, copia **siempre** `index.html` + carpeta `img/` + carpeta `audio/`. Sin ellas, no se verán los logos ni se oirá la narración.

---

## ▶️ Cómo usar

- **Abrir:** doble clic en `index.html` (se abre en el navegador). Recomendado pantalla completa con `F11`.
- **Navegar:** flechas del teclado, barra espaciadora, rueda del mouse, o deslizar (touch). También los botones `‹ ›` inferiores.
- **Narración:** al entrar a cada lámina, su audio se reproduce automáticamente desde el inicio; al cambiar de lámina, el audio anterior se detiene.

### Controles de audio (abajo a la izquierda, en vertical)

| Botón | Función |
| ----- | ------- |
| 🔊 Volumen | Al pulsarlo despliega una barra de volumen vertical |
| ↺ Reiniciar | Reinicia la narración de la lámina actual |
| ▶ / ⏸ | Reproduce o pausa la narración actual |

### Foco de la portada

Botón circular en la portada que alterna el aspecto de toda la presentación:
- **Encendido** → modo claro
- **Apagado** → modo oscuro

La preferencia se recuerda en el navegador.

### Edición rápida de textos

- Pasa el cursor por la **esquina superior derecha** o pulsa la tecla **E** para entrar en modo edición.
- Haz clic en cualquier texto para editarlo y pulsa **Ctrl + S** para guardar (se guarda en el navegador local).

---

## 🗂️ Mapa de láminas y narración

| Lámina | Contenido | Audio |
| ------ | --------- | ----- |
| 1 | Portada | `audio1.mp3` |
| 2 | Objetivo | `audio2.mp3` |
| 3 | ¿Qué es el hostigamiento sexual laboral? | `audio3.mp3` |
| 4 | Ejemplos de conductas inapropiadas | `audio4.mp3` |
| 5 | También por WhatsApp / redes sociales | `audio5.mp3` |
| 6 | ¿Por qué es importante prevenirlo? | `audio6.mp3` |
| 7 | Cómo actuar + cultura de respeto | `audio7.mp3` |
| 8 | Comité de Intervención | `audio8.mp3` |
| 9 | ¡Tu participación es importante! | `audio9.mp3` |
| 10 | Gracias | *(sin audio)* |

---

## 🎨 Identidad visual

Basada en la plantilla corporativa (`plantillappt.pptx`) y los logos oficiales de Consorcio Rovella Inmac.

| Elemento | Valor |
| -------- | ----- |
| Azul corporativo | `#06184A` / `#041643` |
| Rojo (acento / alerta) | `#E10B19` / `#D8232A` |
| Verde (positivo) | `#1FA463` |
| Tipografías | Schibsted Grotesk (títulos) · Hanken Grotesk (texto) |

Los colores se controlan con variables CSS en el bloque `:root` / `#deckStage` al inicio de `index.html`.

---

## 🔧 Notas técnicas

- **Sin dependencias ni instalación:** funciona en cualquier navegador moderno (Chrome, Edge, Firefox).
- **Autoplay del audio:** algunos navegadores bloquean el sonido automático al abrir el archivo; la narración de la lámina 1 arranca sola en cuanto haces el primer clic o pulsas una tecla (o con el botón ▶).
- **Estilo alternativo CRI (teal):** el código incluye una paleta alternativa lista para reactivar (clase `pal-cri`), actualmente no expuesta en la interfaz.

---

*Material de uso interno — Consorcio Rovella Inmac · Prevención del Hostigamiento Sexual Laboral · 2026.*
