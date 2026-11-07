# MPTO 3D · Aeropuerto Internacional de Tocumen

Modelo 3D interactivo del Aeropuerto Internacional de Tocumen (OACI **MPTO** · IATA **PTY**), Panamá, hecho para el estudio aeronáutico. Funciona en el navegador, sin instalar nada, y está construido sobre los planos y datos de la **AIP Panamá, AD 2.1-MPTO**.

> **Herramienta de estudio, no de uso operacional.** No reemplaza a la AIP Panamá vigente y no debe usarse para la navegación aérea ni para el control de tránsito aéreo real.

## Qué incluye

- **Pistas 03R/21L y 03L/21R**: señalización, umbrales, zonas de toma de contacto, PAPI, luces de aproximación y radioayudas (ILS, LMM).
- **Calles de rodaje**: A, B, D, E, F, G, H, J, L, M, Q, T y S1 a S8, con márgenes, letreros y luces de eje y de borde.
- **Plataformas y puestos**: Terminal 1, Terminal 2, Muelle Norte, Remota T1, Remota T2, Aviación General, Carga y Hangar COPA, con sus puestos numerados.
- **Edificios**: terminales con pasarelas, torre de control, SSEI, tanques de combustible, hangares y carga.
- **Entorno**: terreno con imagen satelital alrededor del aeródromo, relieve de las montañas al norte y al este, la costa, el mar y la isla Taboga. Hay casas y árboles solo donde existen, y los puntos cardinales sobre el terreno.
- **Iluminación nocturna**, según la AIP:
  - **Eje de pista**: blanco.
  - **Borde de pista**: blanco, y amarillo en los últimos 600 m.
  - **Fin de pista**: barra roja.
  - **Umbral**: verde.
  - **Calles de rodaje**: eje verde y borde azul.
  - **Otras**: faro del aeródromo y luces de obstáculo.

## Cómo se usa

| Acción | Computadora | Celular / tableta |
|---|---|---|
| Girar la cámara | Arrastrar con clic izquierdo | Arrastrar con un dedo |
| Mover | Clic derecho y arrastrar | Arrastrar con dos dedos |
| Acercar / alejar | Rueda del ratón | Pellizcar |
| Ver información | Tocar una pista, calle, plataforma, puesto o edificio | Tocar |

Barra lateral:

- **Vistas**: vista general, alrededores, desde la torre, terminales, carga y COPA, y finales a cada pista.
- **Explorar**: busca y lista pistas, calles, plataformas y edificios. Al elegir uno se resalta y aparece su ficha con los datos de la AIP: ancho, superficie, PCN, luces y conexiones.
- **Capas**: activa o desactiva etiquetas, luces, letreros, casas, imagen satelital y puntos cardinales.
- **AIP**: datos del aeródromo y fuentes.
- **Noche**: cambia a iluminación nocturna.

La página se ajusta sola al dispositivo. En celulares y equipos modestos aligera el terreno, la vegetación y los efectos visuales, y baja la resolución si hace falta para mantener la fluidez.

## Publicación

Es un solo archivo, `index.html`, que lleva dentro todos los datos y texturas. Para publicarlo en GitHub Pages:

1. Sube `index.html`, `README.md` y `LICENSE` a un repositorio.
2. En **Settings → Pages**, elige la rama `main` y la carpeta raíz.
3. La página quedará en `https://<usuario>.github.io/<repositorio>/`.

Necesita conexión a internet al abrirse, porque carga three.js y la tipografía desde sus CDN.

## Fuentes

- **AIP Panamá, AD 2.1-MPTO**: plano del aeródromo, plano de estacionamiento y atraque, características de pistas y calles, iluminación y radioayudas. Publicada por la Autoridad Aeronáutica Civil de Panamá.
- **Terreno, imagen satelital, casas y relieve**: tomados del proyecto *Meteo ATC 3D*, del mismo autor.

## Tecnología

- [three.js](https://threejs.org) 0.160 (licencia MIT) para el render WebGL.
- HTML, CSS y JavaScript, sin servidor ni base de datos.

## Autor y licencia

**Derek Cuan — "Delta Charlie"** · [github.com/Bugaryy](https://github.com/Bugaryy)

© 2026 Delta Charlie. **Todos los derechos reservados.** Consulta el archivo [`LICENSE`](LICENSE). No se permite copiar, modificar, redistribuir ni vender este proyecto sin autorización escrita del autor.
