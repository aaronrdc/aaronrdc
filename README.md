# Generador de escenarios de futuro

Dinámica de cartas para el Centro de Estudios del Futuro. Se eligen 5 cartas
(tipo de historia, horizonte, temática, evento y a quién o dónde le sucede), se
agregan ideas y Claude escribe una narrativa sencilla con la estructura
implícita de las 4C (contexto, conflicto, clímax y cierre). Después se puede
visualizar con escenas animadas y generar prompts de imagen y de video.

## Dos versiones

| Archivo | Dónde se usa | Cómo se conecta con la IA |
|---|---|---|
| `escenarios-artifact.html` | Publicada como Artifact en claude.ai | Claude desde la propia página, con tu sesión de claude.ai. No necesita claves. No puede llamar a Veo. |
| `escenarios-local.html` | Se abre desde tu computadora (doble clic) | Con tus claves de API en **⚙ Ajustes**: Anthropic para Claude, y Gemini para imágenes hiperrealistas (Nano Banana) y video (Veo 3.1). |

Las dos tienen el interruptor de modo oscuro y claro, el botón **? Consulta**,
las descripciones al pasar el cursor, la escena animada y los prompts.
Cuando cambie una, hay que aplicar el mismo cambio en la otra.

## Versión local

1. Abre `escenarios-local.html` en Chrome o Safari.
2. Entra a **⚙ Ajustes** y guarda tu clave de Anthropic. Se guarda solo en el navegador.
3. Para generar video, guarda también tu clave de Gemini (Google AI Studio).
   Veo requiere facturación activa y cada clip de 8 segundos cuesta dinero.
4. Sin claves, **Copiar prompt** y **Abrir en Claude** siguen funcionando.

## Archivos antiguos

`v1-oscuro.html`, `v2-liquid-glass.html` e `index.html` son las primeras
versiones locales. Ya no reciben mejoras.
