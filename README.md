# Sorteos Heladería Real 🍫

Ruleta interactiva para los sorteos de la **M de chocolates artesanales + café en vasito comestible** de Heladería Real.

## Demo

https://sorteohreal.vercel.app

## Solapas

| Solapa | Participantes | Lista |
|---|---|---|
| **Sorteo 1** | 221 | Participantes de Instagram |
| **Sorteo 2** | 20 | Lista presencial (nombres completos) |
| **Sorteo 3** | 241 | Instagram + presencial, mezclados |

Cada solapa tiene su propia ruleta, su propio ángulo y su propio estado de giro: se puede sortear en una sin afectar a las otras.

### Sorteo 3: dos ganadores

1. Primer giro → **1er ganador**. El cartel ofrece el botón **"Sortear el 2do ganador"**.
2. Al tocarlo, el 1er ganador **sale de la ruleta** (quedan 240) y se gira de nuevo.
3. Segundo giro → **2do ganador**, con su propio cartel y número de ticket.
4. Abajo queda la tira **1° / 2°** con ambos nombres y un botón **↺** para reiniciar el sorteo (vuelve a 241 y borra los ganadores).

## Características

- Ruleta con desaceleración realista, ticks de sonido y aguja que rebota.
- En Sorteo 2 los nombres se dibujan sobre los sectores (se achican solos para entrar).
- Anuncio del ganador con foto del premio, confeti, fanfarria y número de ticket.
- Responsive: móvil vertical, móvil acostado (dos columnas) y tablet.
- 100% estático: un único `index.html` sin build (solo Google Fonts y canvas-confetti por CDN).

## Uso

Abrí `index.html` en el navegador o entrá a la demo. Elegí la solapa y tocá **¡Girar Ruleta!** (o el eje central).

## Deploy

Proyecto de Vercel `sorteohreal`, desplegado desde este repositorio.
Deploy automático activado: cada push a `main` redeploya en Vercel.
