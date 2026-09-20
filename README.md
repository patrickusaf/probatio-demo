# Probatio · demostración pública

Demostración **navegable y con datos totalmente ficticios** de [Probatio](https://psforense.es/software/), la herramienta de gestión
para peritos psicólogos: casos, clientes, documentación, presupuestos, facturas, gestoría, leads y más.

**Pruébala:** https://patrickusaf.github.io/probatio-demo/ · también en [psforense.es/demo](https://psforense.es/demo/)

- Son las pantallas reales de la aplicación, capturadas con datos inventados. No hay servidor, base de datos, cookies ni conexión con nada.
- Puedes moverte por todas las secciones y abrir fichas, listados y facturas. Los botones que guardarían o descargarían algo
  responden «esto es una demostración»: no se guarda nada.
- Ninguna persona, procedimiento, NIF o importe es real.
- El código fuente del producto **no** está aquí: vive en un repositorio privado. Esta carpeta solo contiene el resultado
  (HTML, estilos y la tipografía) que ve quien visita la demo.

## Cómo se genera

No se edita a mano. Se genera desde el repositorio privado de Probatio con `scripts/generar-demo.js`, que recorre una instancia de
demostración y guarda cada página. Cada versión nueva de Probatio actualiza la demo.

## Publicar

Con GitHub Pages: *Settings > Pages > Deploy from a branch*, rama `main`, carpeta `/ (root)`.

## Licencias

- Tipografías: Familjen Grotesk y Source Serif 4, bajo licencia SIL Open Font License 1.1.
- Interfaz y contenido de demostración: © 2026 Patrick Svensson. Todos los derechos reservados.
