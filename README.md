# cuaderno_releases

Versiones públicas de **Cuaderno**, la app de recetas (y de gimnasio, yoga…)
para Android. Aquí solo hay las APK y un `version.json`; el código está en
un repositorio privado.

## Instalar o actualizar a mano

1. Abre la [última versión](https://github.com/EnZaFe/cuaderno_releases/releases/latest)
   desde el móvil.
2. Descarga `cuaderno-X.Y.Z.apk` y ábrela. Si Android lo pide, permite
   instalar apps desde el navegador (o desde Archivos).
3. Si ya tenías Cuaderno, se actualiza **sin perder tus datos**.

## Para la app

La app consulta este archivo para saber si hay una versión nueva:

```
https://github.com/EnZaFe/cuaderno_releases/releases/latest/download/version.json
```

```json
{
  "versionCode": 3,
  "version": "0.1.2",
  "apk": "https://github.com/EnZaFe/cuaderno_releases/releases/download/v0.1.2/cuaderno-0.1.2.apk",
  "sha256": "…",
  "minVersionCode": 1,
  "novedades": "…"
}
```

Las releases las crea automáticamente un *workflow* del repositorio privado
al publicar una versión: no subir nada aquí a mano.
