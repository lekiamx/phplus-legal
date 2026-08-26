# Documentos legales de PH Plus

Política de Tratamiento de Datos Personales de la aplicación **PH Plus**
(`com.phplus.app`), publicada para cumplir el requisito de Google Play de una
política accesible sin credenciales y desde cualquier país.

- **Publicada en:** https://lekiamx.github.io/phplus-legal/
- **Copia servida por el proveedor:** https://phplus-legal.phplus-co.workers.dev/privacidad

## Este archivo no se edita aquí

`index.html` es **una copia**. El original vive en el repositorio del servidor,
en `workers/legal/src/politica-de-privacidad.html`, que es también lo que sirve
el Worker de Cloudflare.

Se publica en dos sitios a propósito —si uno de los dos deja de responder, la
política sigue siendo accesible, y una ficha de tienda no puede quedarse sin
ella— pero eso crea el riesgo de que las dos copias se separen. Un documento
legal con dos versiones distintas en circulación es peor que tener una sola.

Por eso la copia se hace con un script y no a mano:

```
scripts/publicar-politica.sh    # en el repositorio PH_PLUS_Server
```

El script copia el original, avisa si las dos ya diferían y deja el commit
listo. Si alguien edita este archivo directamente, el siguiente uso del script
lo sobrescribe.
