# GSCS · Gaussian Splat Transition Lab

Visualizador de Gaussian Splat con **18 efectos GLSL**, controles de parámetros y reproducción interactiva, diseñado para funcionar como sitio estático en GitHub Pages.

## Abrir

https://inmersoxr.github.io/GSCS/

## Funciones

- 18 efectos GPU (00–17) desde MCMC hasta Tornado.
- Panel de amplitud, frecuencia, turbulencia, rotación, escala, desvanecimiento, brillo y semilla.
- Visualización en puntos, ganancia, fusión puntos → Gaussians, borde y color.
- Reproducción, modo cíclico, progreso manual, duración, espera e interpolación.
- Carga local de modelos **.sog** y **.ply** (no se suben a ningún servidor).
- Exportación e importación de parámetros JSON.
- Visor de código Effect / Hooks / Library.
- Motor PlayCanvas y modelo de ejemplo empaquetados dentro del repositorio. Los archivos de **payload/** son partes del contenido original exportado y se reconstruyen en el navegador.

## Despliegue

El flujo **Deploy GSCS to GitHub Pages** se ejecuta al actualizar `main`. La configuración del repositorio debe tener activado **Settings → Pages → Build and deployment → GitHub Actions** para admitir despliegues.

## Créditos

La implementación de los shaders y la lógica del visualizador se ha recuperado del HTML de exportación de [3DGS Transition Lab, Liquidus Labs](https://liquiduslabs.com/3dgs_translab/) facilitado para este proyecto. Esta adaptación incorpora su propia interfaz de controles. Antes de redistribuir el código más allá de este proyecto, revisar los términos aplicables del autor original.
