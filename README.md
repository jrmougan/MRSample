## Environment

Contedor dos elementos do entorno 3D (chan, obstáculos, decoracións).

## Lighting

Inclúe as luces da escena, como a luz direccional (simula o sol).

## MR Interaction Setup Variant

Centro de control da interacción MR (Mixed Reality):

- **Input Action Manager**: Administra accións dos mandos VR.
- **XR Interaction Manager**: Xestiona as interaccións (coller obxectos, teleportarse...).
- **EventSystem**: Sistema para detectar eventos de UI (clics, toques).

## XR Origin (XR Rig)

Representa o corpo VR no espazo:

- **Camera Offset**: Axuste da altura da cámara.
- **Locomotion**: Xestiona movemento (teleport, movemento continuo).
- **Hands Smoothing Post Processor**: Suavizado do seguimento das mans.

## AR Session

Inicializa subsistemas de Realidade Aumentada (non usado en VR directamente).

## Goal Manager

Administra os obxectivos ou misións dentro da experiencia. (Neste caso xestiona o tutorial por pasos)

## Object Spawner

Permite spawnear obxetos

## UI

Contén os elementos da interface gráfica de usuario (HUDs, menús, botóns).

## Permissions Manager

Xestiona permisos necesarios para a aplicación (cámara, espazo físico, etc.).
