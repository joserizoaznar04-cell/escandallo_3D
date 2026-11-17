# Escandallo 3D

Registro de piezas impresas en 3D (Bambu Lab A1): coste por material y electricidad, producción (pendiente, en proceso, hecho), ventas con extracto en PDF y control de bobinas.

Es una sola página estática (`index.html`), sin dependencias ni paso de compilación. Solo carga jsPDF desde cdnjs al generar un PDF.

## Despliegue en Vercel

1. En Vercel, **Add New → Project** e importa este repositorio.
2. Framework Preset: **Other**. Sin Build Command ni Output Directory.
3. Deploy.

## Datos

Los datos se guardan en el `localStorage` del navegador donde abras la página: no se sincronizan entre dispositivos y se pierden si borras los datos del sitio.

Para pasar datos de un sitio a otro (por ejemplo, desde el artefacto de Claude): **Configuración → Exportar copia (JSON)** y luego **Importar copia** en el otro.
