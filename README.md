# Caja Personal — PWA de registro de gastos e ingresos

App personal instalable en Android para registrar gastos e ingresos al momento, acumular el historial y exportarlo para análisis.

---

## Archivos del repositorio

| Archivo | Función |
|---|---|
| `index.html` | La app completa (HTML + CSS + JS en un solo archivo) |
| `manifest.json` | Configuración PWA — permite instalarla en Android |
| `sw.js` | Service worker — permite usarla sin internet |

---

## Instalación en Android

1. Sube los 3 archivos a un repositorio público en [GitHub](https://github.com)
2. En el repositorio ve a **Settings → Pages → Branch: main → Save**
3. Espera 1–2 minutos. Tu URL será: `https://TU_USUARIO.github.io/NOMBRE_REPO/`
4. Abre esa URL en **Chrome para Android**
5. Chrome mostrará un banner: **"Agregar a pantalla de inicio"**
   - Si no aparece: menú ⋮ → Agregar a pantalla de inicio
6. Confirma. La app aparece en tu pantalla de inicio como cualquier app instalada.

---

## Funciones

- Registro de gastos e ingresos con concepto, monto, categoría y fecha/hora automática
- Historial agrupado por día con resumen diario (gastos / ingresos / neto)
- Balance general acumulado
- Exportar CSV — para análisis con IA o en Excel/Google Sheets
- Respaldo JSON — copia de seguridad de todos los datos
- Restaurar desde respaldo JSON
- Funciona sin internet una vez instalada

---

## Datos

- Se guardan localmente en el almacenamiento de Chrome en tu teléfono
- No se envían a ningún servidor
- Para no perderlos ante un cambio de teléfono o borrado del navegador: usa **Respaldo JSON** periódicamente y guarda el archivo en Google Drive o similar

---

## Exportar para análisis con IA

El CSV exportado tiene este formato:

```
fecha,hora,tipo,categoria,concepto,monto
01/may/2025,09:15,gasto,Alimentación,"Desayuno",85.00
01/may/2025,14:30,ingreso,Otros,"Pago cliente",1500.00
```

Puedes pegarlo directamente en Claude, ChatGPT u otra IA y pedir análisis como: resumen del mes, categorías donde más gastas, comparativa semanal, etc.
