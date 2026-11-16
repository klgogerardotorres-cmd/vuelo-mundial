# Vuelo Mundial

Simulador de vuelo accesible para recorrer el planeta Tierra y visitar 38 monumentos y maravillas naturales, con narración por voz del dispositivo (historia y geografía) y un pasaporte de sellos.

## Control (por estado de contacto)

| Manos apoyadas | El avión… |
|---|---|
| Solo izquierda | gira a la izquierda |
| Solo derecha | gira a la derecha |
| Ambas | sube |
| Ninguna | baja suave hasta una altura segura (configurable: mantener altura) |

- Nunca choca ni hay game over: siempre mantiene una altura mínima sobre el suelo y los edificios.
- Cerca de un monumento, sin manos, el avión lo rodea solo.
- Menú de destinos: izquierda (mantener) = ir al lugar que se muestra; derecha (mantener) = seguir volando. Las opciones pasan solas cada pocos segundos.
- Panel del adulto: mantener 3 s la esquina superior derecha (o tecla P).

## Mapa 3D fotorrealista

1. Crear una cuenta gratuita en https://cesium.com/ion (uso personal no comercial).
2. Copiar el token de **Access Tokens**.
3. En el juego: panel del adulto → *Mapa del mundo* → pegar el token → **Guardar y recargar**.

El token se guarda solo en ese dispositivo. Sin token, el juego funciona con imagen satelital plana (sin edificios 3D).

Recomendado: en Cesium ion, restringir el token a la dirección de esta página (GitHub Pages).

## Créditos

Motor 3D: CesiumJS (Apache 2.0). Modelo del avión: Cesium Air (muestras de CesiumJS). Mapas: Google Photorealistic 3D Tiles vía Cesium ion, Esri World Imagery.
