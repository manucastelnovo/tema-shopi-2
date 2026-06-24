# Tema generado (Refresh adaptado)

Tema de Shopify generado automaticamente con **clonador-shopify**.

## Subir a Shopify

### Opcion A — Integracion GitHub (recomendada)
1. Crea un repo en GitHub y haz push de esta carpeta (los archivos del tema estan
   en la raiz, como exige Shopify).
2. En Shopify Admin: *Online Store > Themes > Add theme > Connect from GitHub*.
3. Selecciona el repo/rama. Shopify sincroniza en ambos sentidos: podras seguir
   editando los bloques desde el editor de temas.

### Opcion B — Shopify CLI
```bash
shopify theme push --store mi-tienda-nueva.myshopify.com --path .
```

## Notas
- Las imagenes ya se subieron a *Files* de la tienda destino y las referencias
  estan reescritas.
- Revisa `overrides.json` (en la carpeta del bot) si quieres ajustar textos/colores
  y volver a ejecutar.
