# 3DDUT AR — tu diseño, parado en la obra

    3ddut-ar/
    ├── index.html      <- la app (interfaz 3DDUT)
    ├── ar-core.js      <- NÚCLEO compartido con MS AR (se copia desde ..\..\_core\ con sincronizar_core.py)
    ├── three.min.js    <- three r160 (UMD)
    ├── sw.js · manifest.json · icon-*.png · .well-known/assetlinks.json (APK TWA)
    └── LEEME.md

Abre OBJ (con colores por vértice o por material + .mtl) y JSON de redes de conductos.
Publicar: commit + push a `main` → https://rodrigodutruel-prog.github.io/3ddut-ar/
APK: proyecto en ..\3ddut-ar-apk (WebView con esta web adentro + vista AR nativa con ARCore). Se recompila y publica con cada versión; el detalle está en ..\..\LEEME_AR.md.
