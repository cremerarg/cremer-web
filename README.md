# Sitio web — Cremer y Asociados

## Estructura

```
index.html            → Página de inicio
empresa.html           → Quiénes somos / historia / valores
divisiones.html        → Exportación de Porotos + Biodiesel
contacto.html          → Datos de contacto
styles.css              → Estilos compartidos por todo el sitio
tableros/
  index.html            → Listado de tableros internos
  tablero_camiones/
    index.html          → cremer.com.ar/tableros/tablero_camiones
```

## Cómo agregar un tablero nuevo

1. Crear una carpeta nueva dentro de `tableros/`, por ejemplo `tableros/tablero_contratos/`.
2. Poner adentro un archivo `index.html` con el contenido del dashboard.
3. Agregar una tarjeta nueva en `tableros/index.html` (copiar el bloque `<a class="division-card">` existente y cambiar textos y el link).
4. Subir los cambios al repositorio de GitHub → el sitio se actualiza solo.

Con esa estructura, la URL pública queda como `cremer.com.ar/tableros/tablero_contratos`.

## Cómo publicar cambios

Este sitio se despliega automáticamente desde GitHub. Cualquier archivo que subas
o modifiques en la rama de producción (main) se refleja en cremer.com.ar en
minutos, sin pasos adicionales.
