# Guía para actualizar automotoresjc.com con Gemini

## Paso 1 — Abrí Gemini
Andá a gemini.google.com

## Paso 2 — Copiá tu HTML actual
1. Andá a https://github.com/kohlkevin13-netizen/automotores-jc
2. Hacé clic en `index.html`
3. Hacé clic en el botón "Raw" (arriba a la derecha del código)
4. Seleccioná TODO (Ctrl+A) y copiá (Ctrl+C)

## Paso 3 — Pedile a Gemini lo que necesitás

### Para AGREGAR un vehículo, pegá esto en Gemini:

```
Tengo esta landing page de autos usados en HTML (te la pego abajo).
Necesito que me devuelvas el archivo COMPLETO con este vehículo nuevo agregado
ANTES del cierre </div> <!-- vehicles-grid -->:

- Marca/Modelo: Toyota Corolla (CAMBIÁ ESTO POR EL AUTO REAL)
- Año: 2020
- Km: 45.000
- Precio: USD 18.000 (o en pesos: $12.000.000)
- Transmisión: Manual o Automática
- Combustible: Nafta
- Color: Blanco
- Categoría: auto (o moto)
- Fotos: toyota-corolla-1.jpg, toyota-corolla-2.jpg
- Badge: Destacado (opciones: Destacado, Premium, Oportunidad, Moto, Recién ingresado)
- WhatsApp: 5491140676031

IMPORTANTE:
- Devolveme el HTML COMPLETO del archivo, no solo el bloque nuevo
- No cambies NADA del resto de la página
- Actualizá el número de "unidades en stock" en el banner de arriba

Acá va mi HTML actual:
[PEGÁ TODO EL HTML ACÁ]
```

### Para ELIMINAR un vehículo:

```
Tengo esta landing page. Eliminá el vehículo "Mercedes-Benz Clase C Coupé"
(CAMBIÁ POR EL NOMBRE DEL AUTO A ELIMINAR) y devolveme el HTML completo.
Actualizá el número de "unidades en stock".

[PEGÁ TODO EL HTML ACÁ]
```

### Para CAMBIAR un precio:

```
Tengo esta landing page. Cambiá el precio del Fiat 500 Lounge a USD 11.000.
Devolveme el HTML completo.

[PEGÁ TODO EL HTML ACÁ]
```

## Paso 4 — Copiá la respuesta de Gemini
Gemini te va a devolver todo el HTML actualizado. Copiá TODO.

## Paso 5 — Subilo a GitHub (se actualiza solo la página)
1. Andá a https://github.com/kohlkevin13-netizen/automotores-jc
2. Hacé clic en `index.html`
3. Hacé clic en el LÁPIZ ✏️ (arriba a la derecha, dice "Edit this file")
4. Seleccioná TODO el contenido (Ctrl+A) y pegá lo nuevo (Ctrl+V)
5. Abajo hacé clic en el botón verde **"Commit changes"**
6. En el popup hacé clic en **"Commit changes"** de nuevo
7. Esperá 30 segundos y entrá a automotoresjc.com — ya va a estar actualizado

## Para subir fotos nuevas
1. Andá a https://github.com/kohlkevin13-netizen/automotores-jc
2. Hacé clic en la carpeta `img`
3. Hacé clic en **"Add file"** > **"Upload files"**
4. Arrastrá las fotos (renombralas SIN espacios ni ñ, ej: toyota-corolla-1.jpg)
5. Hacé clic en **"Commit changes"**

## Badges disponibles (la etiqueta sobre la foto)
- `Destacado` → rojo
- `Premium` → dorado
- `Oportunidad` → verde
- `Moto` → rojo
- `Recién ingresado` → verde
- `Última unidad` → rojo

## Datos del negocio
- WhatsApp: 5491140676031
- Instagram: automotores.j.c
- Zona: San Martín, Provincia de Buenos Aires
