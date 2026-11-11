# 💌 Invitación

Una invitación interactiva en una sola página. Si la persona intenta decir **No**, el botón se escapa: se mueve, se encoge y el **Sí** crece. Después de 100 intentos el **No** se rinde y queda chiquitico. Si aun así lo toca, aparece un motivo de rechazo gracioso (y un poquito triste). Si acepta, se abre WhatsApp con la respuesta lista para enviarte.

## Cómo usarla

1. Abre la página publicada: **https://vaneluuq.github.io/invitacion/**
2. Elige una plantilla (**Romántica**, **Fiesta** o **Elegante**) y llena:
   - el nombre de la persona invitada,
   - el plan,
   - tu número de WhatsApp con indicativo de país (ej. `573001234567`).
3. Toca **Crear enlace de invitación** y copia el enlace (o mándalo directo por WhatsApp).

Los datos viajan dentro del enlace (después del `#`), así que no se necesita servidor ni base de datos.

## Publicar en GitHub Pages

En el repositorio: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

Todo está en `index.html`; no hay que instalar ni compilar nada.
